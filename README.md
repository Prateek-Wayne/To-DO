#To-Do Web Application
This is a simple To-Do Web Application that allows users to create and manage their tasks. The application is built using Python Flask framework and uses SQLite as a database.

##Requirements
To run this application, you will need to have the following installed on your system:

- Python 3.6 or higher
- Flask 1.1.2 or higher
- SQLite 3 or higher
## Installation
- Clone the repository: git clone https://github.com/Prateek-Wayne/To-DO.git
- Navigate to the project directory:cd To-DO
- Install the dependencies :pip install -r requirements.txt
## Usage
Run the Flask application:
* python app.py
Open a web browser and go to http://localhost:5000 to access the To-Do application.
## Features
- User registration and login
- Add, edit, and delete tasks
- Mark tasks as complete or incomplete
- Search for tasks
- Sort tasks by date or priority
## File Structure
............................................................
- ├── app.py
- ├── database.db
- ├── requirements.txt
- ├── static
- │   ├── css
- │   │   ├── main.css
- │   │   └── normalize.css
- │   └── js
- │       ├── main.js
- │       └── mobile-nav.js
- └── templates
-    ├── base.html
-    ├── home.html
-    ├── login.html
-    ├── register.html
-    └── task.html
..............................................................
- app.py - main Flask application file.
- database.db - SQLite database file.
- requirements.txt - file containing all the required Python packages.
- static - directory containing all static files such as CSS, JavaScript, and images.
- templates - directory containing all HTML templates used by the Flask application.
## Contributors
- Prateek-Wayne
##License
This project is licensed under the MIT License - see the LICENSE file for details.




