# Health_Daily

Steps to Execute:
1. Download and Extract zip.
2. option step : create a virtual env in case you dont want to install libraries globally:
     a. run this command in cmd to create a virtual environment: python -m venv venc        [Note : Here venc is virtual environment name. you can keep whatever you like]
     b. run this command to activate virtual environment : .\venc\Scripts\activate
4. install required packages using : pip install -r requirements.txt
5. You might get error while downloading packages so run following command after running the above command:
     a. python -m pip install django
     b. pip3 install django-crispy-forms
     c. pip install Pillow
6. Now run this final command to start the project on local host: python manage.py runserver
    
