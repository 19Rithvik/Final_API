Hi Coder,
This project is a RESTful API for managing a product catalog, allowing users to create, read, update, and delete product information. It is built using FastAPI, SQLAlchemy, and SQLite, providing a modern and efficient approach to API development

Tools and Technologies Used :
•	Programming Language: Python
•	Framework: FastAPI (for building the API)
•	Database: SQLite (for data storage)
•	ORM: SQLAlchemy (for database interactions)
•	Migrations: Alembic (for handling database schema changes)
•	Data Validation: Pydantic (for defining data models and validation)
•	Development Environment: Visual Studio Code (VSCode)
•	Testing: Pytest (for unit testing)

Packages:
fastapi
uvicorn
sqlalchemy
pytest
httpx

How to run :
 1) Run the alembic init alembic command to create alembic folder and check the detailed documentation for changing the code inside init and env.py file
 2) now create initial migration by running alembic --autogenerate -m "inital migration"
 3) run alembic upgrade head
 4) now either run uvicorn main:app --reload or run pytest test.py to test the API
