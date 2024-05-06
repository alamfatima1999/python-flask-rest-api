# Simple Flask API with MySQL Database

This is a simple Flask API integrated with a MySQL database for an e-commerce application.

## Prerequisites

- Python 3.x
- Flask
- Flask-MySQLdb

## Installation

You can install the required dependencies using pip:

```bash
pip3 install Flask Flask-MySQLdb
```
 - pip3 for python 3

## Code Setup

- Clone the repository: ```git clone https://github.com/alamfatima1999/python-flask-rest-api```


## Configure MySQL settings:

   - Open `server.py` in a text editor.
   - Update the MySQL host, username, password, and database name in the configuration section.

## Run the application:

Setup a Virtual Environment (Optional but Recommended):

    Virtual environments help isolate your Python project dependencies.
    Install virtualenv if you haven't already: pip3 install virtualenv
    Create a new virtual environment: virtualenv myenv
    Activate the virtual environment:
        On Windows: myenv\Scripts\activate
        On macOS/Linux: source myenv/bin/activate

Install Flask:

    Once your virtual environment is activated, install Flask using pip: pip3 install Flask

Write Your Flask Application:

    Create a new Python file (e.g., server.py) and write your Flask application code in it. 

Run Your Flask Application:

    Navigate to the directory containing your Flask application script (server.py).
    Run your Flask application script using Python: python app.py
    You should see output indicating that the Flask development server is running, typically on http://127.0.0.1:5000/.

Access Your Flask App:

    Open a web browser and go to http://127.0.0.1:5000/ to see your Flask application running.


## API INFO

### 1. `GET /api/users`
### 2. `GET /api/users/<int:user_id>`
### 3. `POST /api/users`


   

