
pip3 install slowapi
pip3 install fastapi_limiter
pip3 install fastapi-limiter fastapi[all] aiohttp python-dotenv cloudinary
pip3 install fastapi fastapi-limiter sqlalchemy bcrypt jose aiohttp python-dotenv cloudinary redis
pip3 install cloudinary
pip3 install fastapi sqlalchemy pydantic email-validator itsdangerous aiofiles jinja2 aiosmtplib

pip3 install aioredis
pip3 install --upgrade aioredis asyncio


pip3 install --upgrade asyncio

install redis...
https://cloudinary.com/
docker run -d --name redis-stack-server -p 6379:6379 redis/redis-stack-server:latest


docker-compose up -d

python3 01_export_collection.py
python3 02_create_database.py


python3 main.py

uvicorn main:app --reload

http://127.0.0.1:8000/docs



fixing airoredis duplicates
pip show aioredis
manual fix of Timeout exception - change not to inherit from different libs only from one Exception



