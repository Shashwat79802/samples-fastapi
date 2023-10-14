### FastAPI-Postgres CRUD Application

This is a simple CRUD application using FastAPI and Postgres.

## Installation

1. Clone the repository - `git clone https://www.github.com/Shashwat79802/samples-fastapi.git && cd samples-fastapi`
2. Create a virtual environment and install the requirements - `pip3 install -r requirements.txt`
3. Turn on the Postgres instance - `sudo docker-compose up -d`
4. To run application with keploy record mode - `keploy record -c "uvicorn application.main:app --reload"`
5. To run application with keploy test mode - `keploy test -c "uvicorn application.main:app --reload" -t 10`

## Endpoints

1. `GET students/` - Get all students
2. `GET students/{id}` - Get a student by id
3. `POST students/` - Create a student
4. `PUT students/{id}` - Update a student by id
5. `DELETE students/{id}` - Delete a student by id 