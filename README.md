# Django Project Running Guide:-

Editors: Use Visual studio code or Pycharm IDE or Any IDE you comfortable with.

STEP 1: Open integrated terminal.

STEP 2: Run this command to create virtual environment => py -3 -m venv .venv.

STEP 3: Activate virtual environment => .venv/Scripts/activate [.venv\Script\activate if you are using CMD].

STEP 4: Install reuired packages => pip install django mysqlclient pillow (or) pip install -r requirements.txt.

STEP 5: Create a database in mysql in the name "django_db".

STEP 6: python manage.py makemigrations.

STEP 7: python manage.py migrate.

STEP 8: python manage.py runserver.

STEP 9: Open the website in browser.

STEP 10: Back to IDE and turn off the server by click Control + C in terminal.

STEP 11: Create Super User with the command python manage.py createsuperuser.

STEP 12: Run Server Again.

STEP 13: Now Login with the super user.


