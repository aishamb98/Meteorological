# Meteorological

# Django Weather
### Python3, Django web application

# Features!

    - get weather for any city 



## Installation

DjangoWeather requires [Python] v3.6 or up and  [Django] v4.1.4 to run.

Install the dependencies and devDependencies and start the server.





## BackEnd(Django)
#### open cmd and open backend in the DjangoWeather-Bas
```sh
$ cd backend
```
#### create virtualenv
```sh
$ pip install virtualenv
$ virtualenv env
```
#### activate virtualenv
```sh
$ env\scripts\activat

```
#### install all packages
```sh
$ pip install -r r.txt
```

#### migrate 
```sh
$ python3 manage.py migrate
```

#### runserver
```sh
$ python manage.py runserver
```
#### storing all cities
On other terminal in the same Directory  
```sh
$ python post_cities.py
```
--------------------------------------------------------------
## FrontEnd(React)
#### open cmd and open frontend in the DjangoWeather-Bas
```sh
$ cd frontend
```
#### create virtualenv
```sh
$ npm install
or
$ npm install --global yarn
$ yarn install
```
#### activate virtualenv
```sh
$ npm start

```
`----------------------------------------------------------------
## A simple explanation of the code
# BackEnd 
- users > Views.py : is storing user coordinates
- core > models.py : it imports data from the JSON file
- post_cities.py : it opens and read the JSON file
- core > api > serializers.py : converts data cities to JSON data
- core > api > views.py : data that turns into an api
- users > api > serializers.py : converts data user to JSON data 
- users > api > views.py : read and display user data, create an authentication module
- core > tamplates > utils.py : it receives data from the Meteomatics API server

# FrontEnd 
All that is required of React is shown here and it is a very clear file.
Just run the project from cmd according to the commands I sent you above. Provided that the Django(backend file) file is also open on the server in another cmd.



### Development
    Aisha Mohammed Baskran

## Thank you

