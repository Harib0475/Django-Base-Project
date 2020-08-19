# Django BaseProject

Setting up ENV

    pipenv shell
    pipenv install
    
Running server

    python manage.py migrate
    python manage.py runserver
  
Setting up email for reset password

    Create an .env file in root directory and place following lines in it
    
    EMAIL_HOST=smtp.gmail.com
    EMAIL_HOST_USER=<email_address>
    EMAIL_HOST_PASSWORD=<email_password>
    