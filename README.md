# Linux Server Configuration
This project serves to demonstrate live linux server deployment, hosting the earlier itemCatalog.

Server ip address: 34.237.220.166
SSH port : 2200
Complete URL: http://34.237.220.166.xip.io/

# Requirements
Before installing the required below, make sure you have Python3 and pip3. Using pip (under python2) will result in error when running itemCatalog. If python2 is installed just use ``` sudo apt purge python-pip python-dev``` this will remove python2 that came with this linux distribution and files associated with it.  Then run ``` apt-get install python3.5 ``` and after this, run ``` apt-get install python3-pip ```. Now you may use pip3 install *library_name**

- Python3 
- sqlalchemy*
- httplib2*
- oauth2client*
- werkzeug*
- passlib*
- urllib3*
- Flask*
- click*
- psycopg2*

#3 Third party resources:
- Google auth
- Apche2: ``` sudo apt-get install apache2 ```
- libapache2-mod-wsgi-py3: ``` sudo apt-get install libapache2-mod-wsgi-py3 ```
- Postgresql: ``` sudo apt-get install postgresql postgresql-contrib```
- git (git was already installed) you may run, if not installed: ``` sudo apt-get install git ``` 
