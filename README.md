# Linux Server project

Project related to the full stack nanodegree program.
The idea is to deploy an app on a linux machine using aws service.

1. The IP address: http://34.201.6.110/ and SSH port: 2200
2. The complete URL to your hosted web application: http://34.201.6.110/
3. History:

 number       | command executed
------------- | -------------
    1         | adduser grader
    2         | whoami
    3         | su - grader
    4         | cat .ssh/authorized_keys
    5         | cd ..
    6         | cp /home/ubuntu/.ssh/authorized_keys /home/grader/.ssh/authorized_keys
    7         | cd etc/sudoers
    8         | nano etc/sudoers
    9         | nano etc/sudoers.d/grader
   10         | cd
   11         | sudo apt-get install apache2
   12         | nano /var/www/html/index.html
   13         | sudo apt-get install libapache2-mod-wsgi
   14         | nano /etc/apache2/sites-enabled/000-default.conf
   15         | sudo apache2ctl restart
   16         | sudo nano /var/www/html/myapp.wsgi
   17         | sudo apt-get install postgresql
   18         | python
   19         | sudo nano /var/www/html/myapp.wsgi
   20         | sudo nano /var/www/html/lotsofmenu.py
   21         | sudo nano /var/www/html/ds.py
   22         | sudo python /var/www/html/ds.py
   23         | sudo pip install sqlalchemy
   24         | sudo apt-get install sqlalchemy
   25         | sudo apt-get install pip
   26         | apt-get -y install python-pip
   27         | sudo pip install sqlalchemy
   28         | sudo python /var/www/html/ds.py
   29         | sudo python /var/www/html/lotsofmenu.py
   30         | sudo pip install database_setup
   31         | --upgrade pip
   32         | apt-get -y install python-pip3
   33         | sudo nano /var/www/html/database_setup.pyc
   34         | sudo python /var/www/html/lotsofmenu.py
   35         | sudo nano /var/www/html/database_setup.pyc
   36         | sudo python /var/www/html/lotsofmenu.py
   37         | cd /var/www/html/
   38         | ls -l
   39         | nano restaurantmenuwithusers.db
   40         | sqlite
   41         | apt-get install sqlite
   42         | sudo python /var/www/html/lotsofmenu.py
   43         | cd ..
   44         | mkdir FlaskApp
   45         | cd FlaskApp/
   46         | git clone git@github.com:commento/P4ItemCatalog.git
   47         | ls -l
   48         | git clone https://github.com/commento/P4ItemCatalog.git
   49         | ls -l
   50         | cd P4ItemCatalog/
   51         | ls -l
   52         | mv project.py __init__.py
   53         | python database_setup.py
   54         | python lotsofmenus.py
   55         | nano /etc/apache2/sites-enabled/000-default.conf
   56         | nano __init__.py
   57         | sudo apache2ctl restart
   58         | ls -l
   59         | python __init__.py
   60         | intall pip flask
   61         | pip install flask
   62         | python __init__.py
   63         | pip install oauth2client.client
   64         | nano __init__.py
   65         | pip install --upgrade oauth2client
   66         | pip install flask
   67         | python __init__.py
   68         | nano __init__.py
   69         | pip install requests
   70         | python __init__.py
   71         | nano __init__.py
   72         | python __init__.py
   73         | sudo pip install virtualenv
   74         | sudo virtualenv venv
   75         | source venv/bin/activate
   76         | sudo pip install Flask
   77         | sudo python __init__.py
   78         | deactivate
   79         | sudo nano /etc/apache2/sites-available/FlaskApp
   80         | sudo rm /etc/apache2/sites-available/FlaskApp
   81         | sudo rm /etc/apache2/sites-available/FlaskApp.conf
   82         | sudo nano /etc/apache2/sites-available/FlaskApp.conf
   83         | sudo a2ensite FlaskApp
   84         | cd /var/www/FlaskApp
   85         | sudo nano flaskapp.wsgi
   86         | ls -l
   87         | cd P4ItemCatalog/
   88         | ls -l
   89         | sudo service apache2 restart
   90         | cd /etc/apache2/sites-available/
   91         | ls
   92         | cd /var/www/FlaskApp/P4ItemCatalog/
   93         | mv __init__.py init.py
   94         | nano __init__.py
   95         | sudo service apache2 restart
   96         | /etc/apache2/sites-enabled/000-default.conf
   97         | nano /etc/apache2/sites-enabled/000-default.conf
   98         | sudo apache2ctl restart
   99         | cd .
  100         | cd ..
  101         | nano html/myapp.wsgi
  102         | rm myapp.swgi
  103         | sudo myapp.wsgi
  104         | sudo rm myapp.wsgi
  105         | rm myapp.wsgi
  106         | cd html/
  107         | rm myapp.wsgi
  108         | nano myapp.wsgi
  109         | sudo apache2ctl restart
  110         | sudo apt-get install libapache2-mod-wsgi python-dev
  111         | sudo a2enmod wsgi
  112         | cd /var/www
  113         | cd FlaskApp/
  114         | cd P4ItemCatalog/
  115         | nano __init__.py
  116         | sudo python __init__.py
  117         | source venv/bin/activate
  118         | sudo python __init__.py
  119         | deactivate
  120         | sudo nano /etc/apache2/sites-available/FlaskApp.conf
  121         | sudo a2ensite FlaskApp
  122         | cd /var/www/FlaskApp
  123         | sudo nano flaskapp.wsgi
  124         | sudo service apache2 restart
  125         | cd /etc/apache2/sites-enabled/000-default.conf
  126         | rm /etc/apache2/sites-enabled/000-default.conf
  127         | sudo service apache2 restart
  128         | nano /etc/apache2/sites-enabled/000-default.conf
  129         | cd /etc/apache2/sites-enabled/
  130         | ls -l
  131         | nano /var/log/apache2/error.log
  132         | cd /var/www/FlaskApp/
  133         | nano flaskapp.wsgi
  134         | sudo service apache2 restart
  135         | cd P4ItemCatalog/
  136         | ls -l
  137         | rm __init__.py
  138         | mv init.py __init__.py
  139         | sudo service apache2 restart
  140         | nano /var/log/apache2/error.log
  141         | source venv/bin/activate
  142         | ls -l
  143         | python database_setup.py
  144         | pip install sqlalchemy
  145         | python database_setup.py
  146         | python lotsofmenus.py
  147         | python __init__.py
  148         | pip install flask
  149         | python __init__.py
  150         | pip install --upgrade oauth2client
  151         | python __init__.py
  152         | pip install requests
  153         | python __init__.py
  154         | deactivate
  155         | sudo service apache2 restart
  156         | source venv/bin/activate
  157         | pip install sqlite
  158         | pip install sqlite3
  159         | pip install pysqlite
  160         | deactivate
  161         | sudo service apache2 restart
  162         | nano /var/log/apache2/error.log
  163         | source venv/bin/activate
  164         | ls -l
  165         | nano database_setup.py
  166         | nano lotsofmenus.py
  167         | nano __init__.py
  168         | python database_setup.py
  169         | nano lotsofmenus.py
  170         | python lotsofmenus.py
  171         | python __init__.py
  172         | deactivate
  173         | sudo service apache2 restart
  174         | nano /var/log/apache2/error.log
  175         | nano client_secrets.json
  176         | cd ..
  177         | nano flaskapp.wsgi
  178         | sudo service apache2 restart
  179         | nano /var/log/apache2/error.log
  180         | cd ..
  181         | cd FlaskApp
  182         | cp P4ItemCatalog/client_secrets.json .
  183         | sudo service apache2 restart
  184         | nano /var/log/apache2/error.log
  185         | cd P4ItemCatalog/
  186         | nano __init__.py
  187         | sudo service apache2 restart
  188         | history

4. A list of any third-party resources I used of to complete this project:
	- Digital Ocean for the app deployment on ubuntu machine
	- Udacity forum for ssh access issue and sqlite database adaptation
5. Locatation of the SSH key created for the grader user: .ssh/authorized_keys
