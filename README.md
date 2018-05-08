# python3-web
Personal blog system

Local deployment 

    Clone project to local:

    git clone https://github.com/illysa/python3-web.git

    Create and activate virtual environment:

    virtualenv blogproject_env

    # windows
    blogproject_env\Scripts\activate

    # linux
    source blogproject_env/bin/activate


    Install package:

    pip install -r requirements.txt

  
    Imigrate database:

    python manage.py migrate


    Create superuser:

    python manage.py createsuperuser


    Run server:

    python manage.py runserver

    Visit website:
    input 127.0.0.1:8000 in browser

    Log in back end:

    input 127.0.0.1:8000/admin in browser. Sign in with username and password we created before.
