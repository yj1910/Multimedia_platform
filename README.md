# Multimedia_platform
Multumedia platform is website where you can sign up, Create your own channel and upload your videos. Watch others uploaded videos. For database we are using static sqlite DB.

# Local setup
Import the project file in your local. Open in IDE and open terminal

**To install dependencies, run:**
```
python -m pip install --upgrade pip (Upgrading pip)
pip3 install -r requirements.txt
```

**To initialize the Database (sqlite3 file)**
```
del db.sqlite3
python manage.py makemigrations
python manage.py migrate
```

**In order to run this project, execute:**
```
python manage.py runserver
```
open http://127.0.0.1:8000/ on your browser

