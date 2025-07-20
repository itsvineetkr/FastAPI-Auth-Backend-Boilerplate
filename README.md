# FastAPI Authentication Boilerplate Code

## This is a boilerplate code written by Vineet
### Authentication is done using JWT tokens and proper hashing and with the best practices.

To run the server

`python -m venv .venv`
`source .venv/bin/activate`
`pip install -r requirements.txt`
`uvicorn main:app --reload`

This is where the docs will appear:

`http://127.0.0.1:8000/api/v1/docs#/`

By default it uses MongoDB
Connection string can be changed in `env/.evn`
All the environment variables can be changed in `env/.env`