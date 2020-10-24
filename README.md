# django-webapi
Demonstrate web API using django framework

# Setup Virtual Environment
1. Create isolated environment with venv in terminal can call it "venv" : `python -m venv venv`
2. Create .gitignore file in root to ignore datacrunch venv directory
3. Activate virtual environemnt in Windows cmd `venv\Scripts\activate.bat`
4. Install Django with pip in virtual environment `pip install "Django==3.0.*"`
5. In the virtual environment, check if Django is installed correctly:
    a. `python`
    b. `import django`
    c. `django.get_version()`

# Setup Project and Application
6. Create first project: `django-admin startproject datacrunch` or clone project to continue work on Datacrunch Project
7. `cd datacrunch` then `python manage.py migrate`
8. Start development server in project's root folder: `python manage.py runserver`
9. Open http://localhost:8000 to check if the web app is running
10. Create blog application: `python manage.py startapp blog` or clone is fine.
11. Edit settings.py file to include `blog.apps.BlogConfig` under INSTALLED_APPS
12. Migrate database for blog application: `python manage.py makemigrations blog`
13. Sync database with new model: `python manage.py migrate`
14. repeat steps 12 and 13 anytime you modify the models.py file

# Creating Admin Site
15. `python manage.py createsuperuser` in Project Root Folder
16. Go to http://localhost:8080/admin