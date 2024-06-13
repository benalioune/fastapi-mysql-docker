# step1
- create env (ctrl + shift +p) create env pyhton version Mondial
- create requirements.txt
# cmd   
- pip install Flask-SQLAlchemy
- pip install SQLAlchemy
- pip install PyMySQL
- pip install python-dotenv
- pip install uvicorn 
- pip install fastapi
- pip freeze > requirements.txt 

# create models.py
# create database.py
# create main.py

# create mysql user + mysql database 
# grant all access to user root  
ex: 
    GRANT ALL PRIVILEGES ON . TO ‘root’@’%’ IDENTIFIED BY ‘your_password’ WITH GRANT OPTION; GRANT ALL PRIVILEGES ON . TO ‘root’@‘localhost’ IDENTIFIED BY ‘your_password’ WITH GRANT OPTION;

# config 
If you are using Docker to run your FastAPI application and need it to connect to a MySQL server running on your local machine, use the special hostname host.docker.internal to allow Docker containers to access services running on the host machine.

Update your docker-compose.yaml to set the DATABASE_URL environment variable

# create dockerfile
# create docker-compose.yaml


# run 

docker-compose down
docker-compose up --build












