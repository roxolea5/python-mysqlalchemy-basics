# Basic Python Flask & MySQL REST API (with SQLAlchemy)

## Get Started

1. **Navigate to this project's root directory on the command line.**
2. **Get _pip_ (Python Package Installer) with `python3 -m pip install --upgrade pip`**
3. **Install _virtualenv_ with `pip3 install virtualenv`**
4. **Create the folder where virtual environment will be allocated (in my case folder name will is _virenv_)`virtualen virenv`**
5. **Look for "_activate_" file in order to activate the virtual environment. In my case `. virtenv/bin/activate`**
6. **Install with `pip3 install`**
   - flask
   - flask-sqlalchemy
   - flask-marshmallow
   - marshmallow-sqlalchemy
   - pymysql

## Before connection stablishment

1. **Initialize MySQL Service:**

```
sudo service mysql start
```

2. **For the first time, run the following on your sql database**

```
DROP DATABASE IF EXISTS `database_name`;
CREATE DATABASE `database_name` /*!40100 COLLATE 'utf8_spanish_ci' */
```
