### USER STORIES
1. As a Shopper, I want to view a list of products, and select some to purchase.
2. As a Shopper, I want to be able to view product details., price, description, rating, sizes, product image.
3.     The last two user stories in the viewing and navigation category.
    Are met with the presence of a navigation menu.
    That allows users to quickly identify deals and special offers.
    And a real-time shopping bag indicator.
    That allows users to view the total amount of their purchase at any time
    in order to avoid spending too much.
    Although it is possible to make purchases as a guest.
    Our store will allow users to register for an account.
    log in and out
    And reset their password if they've forgotten it.
    Logged in users will have access to a personalized user profile.
    Where they can store their default payment information.
    And view their order history as well as past order confirmations.
    There are user story categories for sorting and searching.
    purchasing and check out. and administration and store management as well
    As we work through this project we'll check off the different user stories
    as we add more and more features to the site.
4. Allow users to create an account and login (allauth)
5. 

### PIP INSTALLS (do these very first thing!)
pip3 install Django==3.2.9
pip3 install django-allauth==0.46.0
pip3 install dj-database-url==0.5.0
pip3 install django-countries==7.2.1
pip3 install django-crispy-forms==1.13.0
pip3 install psycopg2-binary==2.9.2
pip install pillow


Occassionally, 

pip3 freeze > requirements.txt


### DJANGO - NEW PROJECT (dont forget the dot at the end!!!)
django-admin startproject ms4v2 .


### MIGRATIONS
python3 manage.py makemigrations --dry-run
python3 manage.py makemigrations
python3 manage.py migrate --plan <!-- --plan flag, to make sure there is nothing wrong with the models -->
python3 manage.py migrate


### CREATE A SUPERUSER

python3 manage.py createsuperuser


### MAKE DIRECTORIES
mkdir templates
mkdir templates/allauth
