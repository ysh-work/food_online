# Setup project
Create a copy from `.env-sample` & rename to `.env` with your own values.
## Using pipenv
Run `pipenv install`
## Using venv
1. Run `python -m venv venv`.
2. For windows run `.\venv\Scripts\activate.bat`.
3. For linux/mac run `source ./venv/bin/activate`.
4. Inside your virtual environment run: `pip install -r requirements.txt`.

## Run
To run project `python manage.py runserver`.

## Notes
- This project use PostgreSQL by default but you can use any database you want. 