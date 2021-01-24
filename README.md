# Round-2

Multi Tenancy Example:

This repo aims to show how to implement a multi-tenancy architecture using postgres/sqlAlchemy/python/flask


populate the database:
  psql -h [host] -d [database] -U [user] -f "db/init&populate.sql" -W
  example:
  psql -h localhost -d postgres -U postgres -f "db/init&populate.sql" -W

requierements:
# if you wana use a virtual env
python3 -m venv .my_env 
source .my_env/bin/activate

# install requierements
pip install -r requierements.txt

# start the server
python app.py

