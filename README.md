# Travel Website for CS50W Final Project
Hello, Everyone. In this Final Project, I made a simple travel  website where users can book an appointment for their favorite walking tours. By this booking platform, users can view the the possible and open waking tours that are offered and book their appointment.

## Distinctiveness and Complexity
This project utilize Django on the back-end and JavaScript on the front-end as part of the requirements for the final project. The idea of travel tour is very different from the past projects because it has a booking platform and a fresh idea for a travel website especially for backpackers. 

I combined all the knowledge I learned and made a simple travel booking system.

## Files and Directories

Main Directory
    - 'log' - contains sample blog articles
    - 'db.sqlite3' - contains database
    - manage.py
    - 'media' - contains extra photo for blog
    - 'mysite' - contains settings and main url file
    - 'saunt stuff' - other stuff that didn't make in the cut but for future references
    - 'saunterer' - contains all the functionalities of the app
        - 'forms.py' - contains the necessary forms
        - 'models.py' - ORM profile model which has all information of a user
        - 'urls.py' - contains all url paths for profile
        - 'views.py' - contains all view functionalities for profile.
        - 'templates' - all the necessary html files needed for the website
    - 'some.py' - contains task path
    - README.md

## How to run
1. clone the repository
2. cd TravelWebsite
3. python3 manage.py migrate
4. python manage.py runserver
5. Access admin panel by creating superuser :  python manage.py createsuperuser

### Note:
- There are folders which are only for back ups