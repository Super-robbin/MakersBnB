<h1 align="center">MakersBnB</h1>

<p align="center">
In this group project, we were tasked with designing and integrating a SQL database in Python to create a web application called MakersBnB within 4 days.</p>

<p align="center">MakersBnB is an AirBnB replica web application where you can register as a user, log-in as a user, and find and book accomodation or offer accomodation to be booked.</p>

## Our Team

* **[Roberto Quadraccia](https://github.com/Super-robbin)**
* **[Ami Day](https://github.com/ami-day)**
* **[David Ade](https://github.com/D6link)**
* **[Huda](https://github.com/hudaa12])**
* **[Jake Siney](https://github.com/jakesiney)**

## Tech stack

**Frontend:**
<img src="https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white"> <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white">

**Backend:**
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white">


## Setup

```shell
# Install dependencies and set up the virtual environment
; pipenv install

# Activate the virtual environment
; pipenv shell

# Install the virtual browser we will use for testing
; playwright install
# If you have problems with the above, contact your coach

# Create a test and development database
; createdb YOUR_PROJECT_NAME
; createdb YOUR_PROJECT_NAME_TEST

# Open lib/database_connection.py and change the database names
; open lib/database_connection.py

# Run the tests (with extra logging)
; pytest -sv

# Run the app
; python app.py

# Now visit http://localhost:5000/index in your browser
```# Makers_BnB
