# Python-travel- REST API
Travel Destinations REST API (Flask + SQLAlchemy)

This project is a simple REST API built using Flask and SQLAlchemy as part of a learning lab.
The API allows users to Create, Read, Update, and Delete (CRUD) travel destinations stored in an SQLite database.

🧠 What I Learned

This lab helped me understand:

What APIs are and how RESTful architecture works

How clients interact with servers using HTTP methods (GET, POST, PUT, DELETE)

How to build an API using Flask (Python)

How to connect Python to a database using SQLAlchemy

How to test API endpoints using Postman

🚀 Technologies Used
Tool / Library	Purpose
Python (Flask)	Web framework
Flask-SQLAlchemy	Database ORM
SQLite	Local database
Postman	API testing
📦 Installation & Setup

Create & activate a virtual environment (Windows PowerShell):

python -m venv api_env
.\api_env\Scripts\Activate


Install dependencies:

pip install flask flask_sqlalchemy

Run the app:

python main.py

🔌 API Endpoints
Method	Endpoint	Description

GET	/destinations	Get all destinations

GET	/destinations/<id>	Get a single destination

POST	/destinations	Add new destination

PUT	/destinations/<id>	Update destination

DELETE	/destinations/<id>	Delete destination


🧪 Example JSON Body (POST / PUT)

{
  "destination": "Paris",
  "country": "France",
  "rating": 4.8
}
