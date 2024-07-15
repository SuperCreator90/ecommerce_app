# FullStack_Ecommerce_App
A FullStack Ecommerce App built with Django and React. 

## About_this_App
An Ecommerce app where users can purchase products by using their stripe card.  Users are allowed to visit our website and free to look any product details. User needs to create an account on our website to proceed with the payment section. If a user want they can also delete their account anytime (NOTE: With the deletion of a user account all their info like Account details, Address details, Card details will be deleted as well)

The website also provides the flexibility to create a new stripe card if they do not have one, the user can also pay with other user stripe card (if they provide the right email address linked with the card and other card details like Card Number, Exp Month, Exp Year and CVC). The user can also detete their stripe card if they like (Caution: With the deletion of their stripe card their account related to that card will also be deleted as well). 

### Other_Functionalities
- Used JSON web tokens to achieve the authentication checks in the website.
- Strict Security Checking behind the scenes during the Card Creation and Payment Process.
- JSON Token gets checked for every single request made on the website (except products list and product details page)

## Installation
after downloading/cloning the repository code follow below steps:
* (NOTE: your need to mention your own stripe secret api key and publishable key in django to run the project)

### Backend
* (for both linux and windows)
1) Move in backend folder through terminal and run following commands,

`python3 -m venv env` (for windows --> `python -m venv env`) 

`source env/bin/activate` (for windows --> `env\scripts\activate`)

`pip install -r requirements.txt` (same for both)

`python manage.py runserver` (same for both)

### Frontend
* (for both linux and windows)
2) Move in frontend folder through terminal and run follwing commands

`npm i`

`npm start`

## All set ! Happy coding :)

<p><a href="#top">Back to Top</a></p>

