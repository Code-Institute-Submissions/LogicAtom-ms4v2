# MS4v2 - December 15, 2021 

(Updated December 30, 2021)
(Updated January 3,4,5,6,7,10 - 2022)
Created to show Django and Python e-commerce website.

## LIVE SITE:  https://akoz-ms4v2.herokuapp.com/ 

## UPDATES
Adding TESTING PROCEDURES section with associated screenshots, and a basic description for each.<br />
Adding NEW SCREENSHOTS for the Testing Procedures section<br />
Adding CODE VALIDATION URLs<br />

## 👷 Built with these Technologies
Python3, Django, HTML5, CSS3, PostGres, AWS, STRIPE, JS.

## TESTING PROCEDURES
1. UI: Adding items to shopping bag = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/add_to_bag_working.png
2. AUTH: Authentication Error = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/checkout_auth_fail.png
3. AUTH: Successful connection with Heroku CLI = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/heroku_cli.png
4. Disabling Heroku from collection static media files, because static files are stored in AWS = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/heroku_config_set_disableCollectStatic.png
5. Pushing git to Heroku directly = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/heroku_gitPush_working.png
6. After migrating files to Heroku, Test to ensure all files made it there = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/heroku_migrations_noGo.png
7. UX: Testing to see how the landing page looks = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/main_nav_working_and_toasts_working.png
8. TEST Error with Python code = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/product_detail-add_to_bag_error.png
9. Editing products = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/product_edit.png
10. SEARCH QUERY for Specific product types = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/search_query_jeans_working.png
11. Connecting the SHOP NOW button to the Products Page = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/wire_up_shop_now_button_to_products_page.png
12. Connecting the SHOP NOW button to the Products Page (Success) = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/ShopNowButtonToProducts-Success.png
13. Adding new products via Django Administration, as shown on the project main site = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/test_django_add_product-confirm.png
14. Successful products added via Django Administration, as shown on the Django Administration = https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/test_django_add_product.png<br />

Screenshots folder = https://github.com/LogicAtom/ms4v2/tree/main/media/screenshots
<br />

## USER STORIES
1. As a Shopper, I want to view a list of products, and select some to purchase.<br />
2. As a Shopper, I want to be able to view product details., price, description, rating, sizes, product image.<br />
3. a.  The last two user stories in the viewing and navigation category.<br />
    Are met with the presence of a navigation menu.<br />
    That allows users to quickly identify deals and special offers.<br />
    And a real-time shopping bag indicator.<br />
    b. That allows users to view the total amount of their purchase at any time
    in order to avoid spending too much.<br />
    c. log in and out<br />
    And reset their password if they've forgotten it.<br />
    d. Our store will allow users to register for an account.<br />
    e. Although it is possible to make purchases as a guest.<br />
    f. Logged in users will have access to a personalized user profile.<br />
    g. Where they can store their default payment information.<br />
    And view their order history as well as past order confirmations.<br />
    h. There are user story categories for sorting and searching,<br />
    purchasing and check out. 
    i. Administration and store management.<br />
    
4. Allow users to create an account and login (allauth)<br />
5. All users/shoppers to find products without having to search through all the products.<br />
6. As an administrator be able to access and edit products as well as be a shopper.<br />


(Updated January 6, 2022)<br />
## TESTING USER STORIES
1. As a Shopper, I want to view a list of products : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStories1_asUserViewProducts.png<br />
2. As a Shopper, I want to be able to view product details, price, description, rating, sizes, product image : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/userStories2_productDetails.png<br />
3.  a. That allows users to quickly identify deals and special offers, as well as see the real-time shopping bag indicator : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3_viewDeals.png<br />
    b. That allows users to view the total amount of their purchase at any time in order to avoid spending too much : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3_ViewTotalCost.png<br />
    c. log in and out : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3b_logout.png<br />
                        https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3c_logoutConfirmation.png<br />
                        https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3c2_SuccessTOASTmsg.png<br />
    d. Register : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3d_Register_Login.png<br />
    e. Make purchases as a Guest : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3e_PurchaseAsGuest.png<br />
    f. Logged in users will have access to a personalized user profile : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3f_UserProfile.png<br />
    g. Where they can store their default payment information. And view their order history as well as past order confirmations. : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3_makePurchases_TestKey.png, https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3_Profile_wOrderHistory.png <br />
  h. There are user story categories for sorting and searching : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3h_SearchingAndSorting.png<br />
  i. Administration and store management : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting3i_admin_mngmt.png<br />
4. Allow users to create an account and login (allauth) : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting4_AllowSignupRegistration.png<br />
                                                  login : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting4_AllowSignIn_Login.png<br />
5. All users/shoppers to find products without having to search through all the products : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting5_FindProductsEasilyCRUD.png<br />
6. As an administrator be able to access and edit products as well as be a shopper : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting6_Admin_Shopper.png<br />
                                                                 change products   : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/UserStoriesTesting6_Admin_Shopper_ChangeProduct.png<br />


A user cannot delete a product if they are not a superuser : https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/nonAdmin_CRUD_directLinkDelete_NoGo.png

Admin CRUD Delete direct link:
https://akoz-ms4v2.herokuapp.com/products/delete/177/ <br />


### CODE VALIDATION
 CSS = https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fakoz-ms4v2.herokuapp.com%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en<br />
 HTML = https://validator.w3.org/#validate_by_input<br />
 HTML = https://validator.w3.org/nu/?doc=https%3A%2F%2Fakoz-ms4v2.herokuapp.com%2F<br />
 https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/CodeValidation_NoIssuesCompleteFinal.png

 
    ##### Testing Python code using Python Tutor at https://pythontutor.com/visualize.html#mode=edit
 
### WIREFRAMES
Wireframing via screenshot:  https://github.com/LogicAtom/ms4v2/blob/main/media/screenshots/ms4Wireframes.png<br />

### PIP INSTALLS (do these very first thing!)
pip3 install Django==3.2.9<br />
pip3 install django-allauth==0.46.0<br />
pip3 install dj-database-url==0.5.0<br />
pip3 install django-countries==7.2.1<br />
pip3 install django-crispy-forms==1.13.0<br />
pip3 install psycopg2-binary==2.9.2<br />
pip install pillow<br />
pip3 install stripe<br />
pip3 install gunicorn<br />


### Capture and save the project code libraries, so they are available to everyone who opens this project as a clone or fork :)
pip3 freeze > requirements.txt


### DJANGO - NEW PROJECT (dont forget the dot at the end!!!)
django-admin startproject ms4v2 .


### CREATE A SUPERUSER
python3 manage.py createsuperuser
(This is for the Django Administration)


### MAKE DIRECTORIES
mkdir templates<br />
mkdir templates/allauth<br />


### COPY PATH
To find your allauth path in Terminal type:

python


then type:

help('allauth')


allauth will display an ASCII logo and info about your path :)

__________________________________________


Update the provided command with the path you just copied. eg: cp -r [your site-package path]/allauth/templates/* ./templates/allauth/

#### Next step
right click on templates directory, and create base.html file. Will use BootStrap Starter Template.

### BOOTSTRAP
https://getbootstrap.com/docs/4.4/getting-started/introduction/#starter-template

### CREATE NEW APPS
python3 manage.py startapp home<br />
python3 manage.py startapp products<br />
python3 manage.py startapp bag<br />
python3 manage.py startapp checkout<br />
python3 manage.py startapp profiles<br />



We need a templates directory inside the home app.<br />
So let's use 

mkdir -p home/templates/home

  to create parents as required.

  and then right click on inner home directory and right click to create a new file named:  index.html


mkdir static

mkdir media

mkdir static/css

new file base.css


mkdir -p products/templates/products (so Django knows which app these belong to, don't type this parenthesis text or parenthesis)


 ### CREATE VIEWS
 views.py

 views.py is the file used to render new files


 ### RESOURCES
 https://help.heroku.com/O0EXQZTA/how-do-i-switch-branches-from-master-to-main<br />
 https://stripe.com/docs/testing#cards<br />
 
 
 ## SOFTWARE USED TO CREATE THIS PROJECT
 Python: https://www.python.org/<br />
 Django: https://www.djangoproject.com/<br />
 HTML5: https://whatwg.org/<br />
 CSS3: https://www.w3.org/<br />
 CSS3 additional Software:  (Bootstrap)https://getbootstrap.com/<br />
 Javascript: https://www.mozilla.org/en-US/<br />
 Jinja: https://jinja.palletsprojects.com/en/3.0.x/<br />
 
 ## CLOUD SERVICES
 GitPod: https://www.gitpod.io/<br />
 GitHub: https://github.com/<br />
 Heroku: https://www.heroku.com/<br />
 AWS: https://aws.amazon.com/?nc2=h_lg<br />
 Stripe: https://stripe.com/<br />
 
 ### WEB TOOLS
 Google Fonts: https://fonts.google.com/<br />
 Kaggle (sample databases): https://kaggle.com<br />
 JSON Formatter: https://jsonformatter.org/<br />
 Django Secret Key Generatorhttps://miniwebtool.com/django-secret-key-generator/<br />
 Diff Checker: https://www.diffchecker.com/<br />
 Python Tutor: https://pythontutor.com/visualize.html#mode=edit<br />
NodeJS - https://nodejs.org/en/download/ = Dependency Manager<br />
JQuery - https://jqueryui.com/ = Hamburger Mobile Side Menu<br />
Materialize CSS - https://materializecss.com/ = Enhance UI/UX<br />
Amazon Web Services - https://aws.amazon.com/ = Database Connector <br />
[Git](https://git-scm.com/ "Git") : Version Control System <br />
[GitPod](https://gitpod.io/ "GitPod") : IDE <br />
FontAwesome.com = Custom Icons : https://fontawesome.com<br />
Random Keygen https://randomkeygen.com/<br />
Favicon = https://www.favicon.cc/?action=icon&file_id=957941<br />
Wireframing/Data Modeling Software = https://dbdiagram.io/d/61dc77d2f8370f0a2eee9b0f/<br />

 ### ERRORS
 In case any errors happen, these are common places to figure it out:<br />
 1.  foreign keys, products folder(app), models.py<br />
 2.  bigautofield. *RESOLVED* via last line of code in settings.py (apparently its related to django version).<br />

### MIGRATIONS (changes to models)<br />
python3 manage.py makemigrations --dry-run<br />
python3 manage.py makemigrations<br />
python3 manage.py migrate --plan <!-- --plan flag, to make sure there is nothing wrong with the models --><br />
python3 manage.py migrate<br />

python3 manage.py showmigrations<br />

### LOAD DATA (to use the fixtures)<br />
python3 manage.py loaddata categories<br />

python3 manage.py loaddata products<br />

## REMINDERS<br />
django.db.models.BigAutoField = products, apps.py = *RESOLVED* by adding this to the end of the settings.py file:  DEFAULT_AUTO_FIELD = 'django.db.models.AutoField'<br />

django/forms/widgets/attrs.html = attributes<br />

templates/base.html  = commented out stripe until actually used.<br />

accounts/broken/ = displays allauth links<br />

css > Bulma = keeps fontawesome aligned<br />

bag/checkout-buttons.html = need to add checkout url = RESOLVED*<br />

checkout/models.py = profiles, might cause problems as its not built yet. = WORKING*NoErrors<br />

checkout/forms.py = attrs, args, kwargs<br />


## Credits and Acknowledgements

[Code Institute](https://codeinstitute.net/ "Code Institute")Code Institute - FullStack Boot Camp - Most of the code and instructions written by Code Institute, I cannot take credit for the code, only the customization of the code is actually mine.
<br />
Code Institute - for having me create a Python3, Django - Full-Stack MileStone4 project

Code Institute - Tutors for all your help..you rock!<br />
Tutors:<br />
Code Institute Tutors (Rebecca) = AWS, ACL's, Stripe Docs, Heroku CVARs, Code Validation :)<br />
Code Institute Tutors (Alan) = Django Admin Model and Project Migrations. :)<br />
Code Institute Tutors (Ed) = Django and Site Views and Templates. :) <br />
Code Institute Tutors (Sheryl) = Django Environment Variables., and Heroku help. :)<br />
Code Institute Tutors (Jon) = Explaining User Stories and its purpose in detail :)<br />

Code Institute - Student Care Team and Advisers..You are the most amazing people and I couldn't get this far without you!<br />

stackoverflow https://stackoverflow.com/ - For all of the custom questions and answers.

Akshat Garg - My Mentor for Software Development from Code Institute ... Thank you so very much for everything!! :)


### Educational Acknowledgements
Palmetto Goodwill - Grant Funder (my beautiful angels!)
Palmetto Goodwill - COC https://palmettogoodwill.org/coc/, Thank you for letting me use your computers and internet for a few days to work on this project!
<br />
Code Institute - https://codeinstitute.net/global/ - Web Development School - You are the best School!
<br />
Ed2Go/Cengage - https://www.ed2go.com/ - Online Courses - You brought it all together, and offered the course. Awesome!
<br />
Charleston County Public Library - https://www.ccpl.org/- Thank you for letting me borrow around 100 books, and using your computers and internet, I wouldn't have finished this project without you!
<br />


## 🧑🏻 Code Developer
**Anthony Kozloski**
- 🌌 [Profile](https://github.com/LogicAtom "Anthony Kozloski")
