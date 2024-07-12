python3 -m venv part_1
python3 -m venv part_2
source part_1/bin/activate

pip3 install scraper
pip3 install django
pip3 install sqlalchemy_utils
pip3 install --upgrade django
pip3 install python-decouple


python3 01_create_database.py
uvicorn main:app --reload
# create django project
django-admin startproject quotes_project
cd quotes_project

# create django App
python3 manage.py startapp quotes

python3 ./quotes_project/manage.py makemigrations
python3 ./quotes_project/manage.py migrate

# create admin user
python3 ./quotes_project/manage.py createsuperuser

python3 03_fill_out_tables.py


python3 ./quotes_project/manage.py runserver

pip3 install psycopg2
python3 01_create_database.py

pip3 install fastapi
 
pip3 install itsdangerous

pip3 install aiosmtplib

 
pip3 install jose

pip3 install Crypto


uvicorn main:app --reload

http://127.0.0.1:8000/docs