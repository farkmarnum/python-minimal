# Python basic template

## Setup

After cloning:

    python -m venv .v

To enter the virtual environment and install dependencies:

    source .v/bin/activate
    pip install -r requirements.txt

To add new packages:

    pip install <package names>

To store newly installed packages:

    pip freeze > requirements.txt

To exit the virtual environment:

    deactivate

## Running

    python main.py
