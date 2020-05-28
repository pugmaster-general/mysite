This project is based on the tutorial found on:

https://docs.djangoproject.com/en/3.0/

© 2005-2020 Django Software Foundation and individual contributors. Django is a registered trademark of the Django Software Foundation. 

In order to run the polls website you will need the following:

- Python 3 Installed
> check version in ubuntu/linuz with:
>
> python -V

- Django installed (can also be part of a virtual environment)
> to install:
>
> python -m pip install django
>
> to check version:
>
> python -m django --version

To run the polls website on a private development server:
- navigate in a terminal into the top mysite folder,
    - it contains the manage.py file
- run the following (this is on linux)
> python manage.py runserver

To view the polls, while server is running:
- navigate in any browser to 127.0.0.1:8000/polls/

To access the admin interface for the website:
- navigate in any broswer to 127.0.0.1:8000/admin/
- Log in information:
    - username: admin
    - password: pugpugpug
    
## Test Update