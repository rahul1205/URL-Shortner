## Notes

- Implemented basic URL shortner
- Tried implementing Redis caching but couldn't get redis to work on windows after multiple tries

## Setup

- Change the credentials for database in `settings.py`
- Create a virtualenv
- Install the requirements `pip install -r requirements.txt`
- Update settings.py with your own PostgresSQL credentials
- Create the database in PostgresSQL `CREATE DATABASE shortener;`
- Run `python create_db.py` to setup the table

Run the app with `python main.py`
