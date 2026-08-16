# MDN-Library-Django
A Django-based library management application inspired by Mozilla's MDN Local Library tutorial. Built as a hands-on project for developing practical Python/Django, database, authentication, and web application security skills.



<img width="1180" height="766" alt="local_library_model_uml" src="https://github.com/user-attachments/assets/469c1f43-fa76-4ec8-815b-c4a8123618c9" />

<img width="1261" height="706" alt="Libary - SS1" src="https://github.com/user-attachments/assets/9f812e28-1fcf-4e36-87c4-c98dc5bb1c19" />
<img width="1675" height="716" alt="Library - SS2" src="https://github.com/user-attachments/assets/d6dd4495-c919-4f07-b067-4ee5ed0c20a0" />

Quick Start



To get this project up and running locally on your computer:

    Set up the Python development environment. We recommend using a Python virtual environment.

        Note: This has been tested against Django 3.10 (and may not work or be "optimal" for other versions).

    Assuming you have Python setup, run the following commands (if you're on Windows you may use py or py -3 instead of python to start Python):

    pip3 install -r requirements.txt
    python3 manage.py makemigrations
    python3 manage.py migrate
    python3 manage.py collectstatic
    python3 manage.py test # Run the standard tests. These should all pass.
    python3 manage.py createsuperuser # Create a superuser
    python3 manage.py runserver

    Open a browser to http://127.0.0.1:8000/admin/ to open the admin site
    Create a few test objects of each type.
    Open tab to http://127.0.0.1:8000 to see the main site, with your new objects.
