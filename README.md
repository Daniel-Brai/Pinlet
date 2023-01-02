# Pinlet
An image sharing and bookmarking social platform where users  can share their favorite images something akin to Pinterest

## How to run
- Local Deployment
1. On your local machine, make sure you have Python and SQLite3 installed
2. Download, extract the zipped master file of this project and navigate to root directory of this project
3. On the terminal of your choice, create a virtual environment with the command `python -m venv .venv`
4. In your virtual environment, run the command `python -m pip install` to download the dependencies of the project
5. Create a admin user using the command `python manage.py createsuperuser` and follow the prompts
6. Run the local server to view the project using the command `python manage.py migrate && python manage.py runserver`
