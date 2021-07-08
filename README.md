# PythonFlaskProj001

* Set up your initial environment

Install Python 3.6 or higher. check your Python version is 3.6 or higher:

py -3 --version

* Clone the sample

Clone the sample repository using the following command and navigate into the sample folder. (Install git if you don't have git already.)

git clone https://github.com/ayhansevimli/PythonFlaskProj001

* Navigate into in the python-docs-hello-world folder:

cd PythonFlaskProj001

* Create a virtual environment and install dependencies:

py -3 -m venv .venv

.venv\scripts\activate

pip install -r requirements.txt

* flask run

By default, the server assumes that the app's entry module is in app.py, as used in the sample.

If you use a different module name, set the FLASK_APP environment variable to that name.

If you encounter the error, "Could not locate a Flask application. You did not provide the 'FLASK_APP' environment variable, and a 'wsgi.py' or 'app.py' module was not found in the current directory.", make sure you're in the python-docs-hello-world folder that contains the sample.

* Open a web browser and go to the sample app at http://localhost:5000/. The app displays the message Hello, World!.

