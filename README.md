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
1 Run the command alembic init alembic to create the Alembic folder, and check the detailed documentation for modifying the code inside the init.py and env.py files.
2 Create the initial migration by running alembic revision --autogenerate -m "initial migration".
3 Run alembic upgrade head.
4 Create another migration with alembic revision --autogenerate -m "add column category" and again run alembic upgrade head.
5 After creating the two migrations, either run uvicorn main:app --reload or run pytest test.py to test the API.
