Project Name

Short description or overview of your project.
Setup

To ensure a clean and isolated environment for your project, it's recommended to use a virtual environment.
Creating a Virtual Environment

bash

# Navigate to your project directory
cd /path/to/your/project

# Create a virtual environment named 'venv'
`python -m venv venv`
Activating the Virtual Environment
`source venv/bin/activate`

Installing Dependencies

Once the virtual environment is activated, you can install project dependencies using pip.
`pip install -r requirements.txt`

Deactivating the Virtual Environment

To deactivate the virtual environment, simply run:
`deactivate`

# Usage
To start the server simply run(inside the venv):
`python manage.py runserver`
Then go to localhost:8000/graphql to query the api