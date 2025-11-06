# HTMX Playground

Playing around with HTMX and a Flask backend server.

## Getting Started

1. Make sure that you have the latest version of python and pip installed.
2. Create the venv environment and start it in the terminal

`python3 -m venv .venv`

`. .venv/bin/activate`

2. Install the necessary pip packages from the requirements.tx.

`pip install -r requirements.txt`

3. Start the server in debug to ensure changes are watched.

`flask --app app --debug run`

"app" after --app refers to the `app.py` file.

4. The server should open on http://127.0.0.1:5000 if that port is not already used.

### Formatting

To format files, run:

`npm run format`

### Installing New PIP Packages

When installing new packages, make sure to add them to the requirements.txt.

`pip freeze > requirements.txt`
