# Harvard's CS50 Web Programming with Python and Javascript

# * Capstone project by Rafael Loreto *
Project Name: Travel Booking Website
Project Completed: 28 August 2021

# About
In my final project I made a simple travel website where users can book an appointment for their favorite walking tours. By this booking platform, users can view the the possible and open waking tours that are offered and book their appointment. Users are presented of the available places in india for walking tours and by clicking the booking platform they will be transferred to contact page. The simplicitiy of this website targets people who are non-techie or unfamiliar with the booking platforms.

## Distinctiveness and Complexity
This project utilize Django on the back-end and JavaScript on the front-end as part of the requirements for the final project. The idea of travel tour is very different from the past projects because it has a booking platform and a fresh idea for a travel website especially for backpackers. This is the combination of the previous project, meticulously integrated all I learned. This site is mobile responsive with the use of Bootstrap as a framework to help my project to load fast and easier. All HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels, etc. have given my project a good support for JavaScript and Python. On the surface, what makes this project more complex than previous one's is its detailed UI, allowing users to navigate with ease. It also features blog page which the owner or the team of the website can post which will help the users to know more about the place and be engaged on a specific place. 

Once a user has chosen a walking tour, he or she will then be directed to Contact Us page where they can message the admin for possible booking dates and other types of queries. The Admin of the website will then retrieve the booking over the Django Admin and check if the dates are available for booking which they will be sending a reply to their queries.

## Why this project?
I created this project because of my passion in traveling. Though there are already lots of travel website out there that exist, I can say that making another travel website by my own hand is a major feat for me. Walking tours are usually rare in website, I decided to create solely for this purpose. By having its own booking system, this will be distinct to mainstream travel website that are too much to take when checking out to do's. Though, I admit that my projecgt has tons of things to improve like any other professional booking website has to offer, I am proud that this is a small step for me towards solving the needs of travelers. 

## Files and Directories
The following is the file hierarchy of my project. Default project files are ommitted.
`blog` - folder data for the blog part and whole text data.
    `__init___.py` - lets the Python interpreter know that a directory contains code for a Python module.
    `__pycache__` - stores temporary files created when execution of the python code is triggered.
    `admin.py` - use to display models in Django Admin Panel
    `apps.py` - generic entry point for Python applications and typically run.
    `migrations` - Python files containing definitions of old models to write them to Django
    `models.py` - a part of web applications to access and manage dataa through Python objects.
    `static` - these are collected static files for each of the application or places into a single folder
    `templates` - templates for article.html, blog.html and post.html
    `urls.py` - includes all applications urls.
    `views.py` - contains all application views.

`db.sqlite3` - contains database file stored in the SQLite f3 format which includes data records, data types and values which are used to store embedded SQL.
`manage.py` - a command utility file that lets you interact within the project with Python and Django. A tool for executing Django specific tasks.
`media` - this contains default images for the website, and here will be saved all users photos.
`mysite` - contains folders which the main conrol for front-end part of the website
    `settings.py` - holds the configuration values of my web project for it to work.
    `urls.py` - includes all application urls.
    `wsgi.py` - Djangos primary deployment platform. It specifies how a web server communicates with web applications and how they behave.
    `__pycache__` - stores temporary files created when execution of the python code is triggered.
    `__init__.py` - lets the Python interpreter know that a directory contains code for a Python module.

`saunterer` - core folder of the web application is stored here. including front and back end service.
    `__pycache__` - stores temporary files created when execution of the python code is triggered.
    `__init__.py` - lets the Python interpreter know that a directory contains code for a Python module.
    `admin.py` - use to display models in Django Admin Panel
    `forms.py` - call back contact form for booking through the Python module.
    `apps.py` - generic entry point for Python applications and typically run.
    `migrations` - Python files containing definitions of old models to write them to Django
    `models.py` - a part of web applications to access and manage dataa through Python objects.
    `static` - these are collected static files for each of the application or places into a single folder
    `templates` - templates for article.html, blog.html and post.html
    `urls.py` - includes all applications urls.
    `views.py` - contains all application views.
    
`README.md` - contains all the information for the user about the CS50W Project and its hierarchy files.

## How to run the application

1. Clone the repository
2. Change directory to TravelWebsite 
```
cd TravelWebsite
```
3. Initialize the database with makemigrations, migrate, then create superuser.
```
python3 manage.py migrate
python3 manage.py createsuperuser
```
4. Launch the Django server. If set up correctly, server will launch on http://127.0.0.1:8000/.
```
python3 manange.py runserver
```
