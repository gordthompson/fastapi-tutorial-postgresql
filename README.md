# fastapi-tutorial-postgresql

The FastAPI SQL database tutorial 

https://fastapi.tiangolo.com/tutorial/sql-databases/

modified to use `postgresql+asyncpg` and real async calls.

### How to run:

To launch uvicorn:

```
uvicorn sql_app.main:app --reload
```

Then load the fancy interactive docs page at

http://localhost:8000/docs

### Notes:

- Tweak `SQLALCHEMY_DATABASE_URL` in database.py to connect
to your PostgreSQL instance.