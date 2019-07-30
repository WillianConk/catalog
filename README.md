# Item Catalog Project

I have made this project using https://github.com/udacity/OAuth2 as a base, so it is a restaurant catalog which features an authentication with Google.
Users are able to CRUD restaurants, and restaurant entries (Like dishes, desserts, beverages and stuff like that).

Users are only able to see their own information.

Authentication is provided by Google.

## DISCLAIMER

Following the udacity code of conduct, I hareby declare that I have used the following projects to build this project:

- https://github.com/udacity/OAuth2.0 As a base and guideline
- https://github.com/nauvalazhar/bootstrap-4-login-page Used it for the login page.


## Install instructions

- Clone this repository
- navigate to the /vagrant folder
- install pip for python 2 ( https://linuxize.com/post/how-to-install-pip-on-ubuntu-18.04/ )
- install flask with pip (pip install flask )
- install sqlalchemy with pip (pip install sqlalchemy )
- install google-auth with pip ( pip install --upgrade google-auth )
- install requests with pip ( pip install requests )
- type python database_setup.py to initialize the database.
- run python project.py

Project is now available at http://localhost:5000

## Important endpoints:

- http://localhost:5000/restaurant/JSON (Users can retrieve all their restaurants in JSON format)
- http://localhost:5000/login (Users can login)
- http://localhost:5000/logout (Users can logout)
- http://localhost:5000 (Users can navigate through the system)
