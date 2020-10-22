# django-webapi
Demonstrate web API using django framework

1. Create isolated environment with venv in terminal can call it "venv" : `python -m venv venv`
2. Create .gitignore file in root to ignore datacrunch venv directory
3. Activate virtual environemnt in Windows cmd `venv\Scripts\activate.bat`
4. Install Django with pip in virtual environment `pip install "Django==3.0.*"`
5. In the virtual environment, check if Django is installed correctly:
    a. `python`
    b. `import django`
    c. `django.get_version()`

6. Create first project: `django-admin startproject datacrunch`