# flask-sqlalchemy-postgres
Basic microservice with flask, sqlalchemy, and postrgres

Used this as a guide:
https://www.youtube.com/watch?v=PTZiDnuC86g


Using Python 3:
$ python3 —version

Install pipenv package manager:
$ pip3 install pipenv

Create project folder to create pipfile, virtual env, and activate it:
$ pipenv shell

To exit/deactivate pipenv environment:
$ exit

Install libraries and binaries:
$ pipenv install flask flask-sqlalchemy flask-marshmallow marshmallow-sqlalchemy psycopg2-binary

Migrate DB schema:
$ python
>>> from app import db
>>> db.create_all()



TO DO:


Deal with this: WARNING: This is a development server. Do not use it in a production deployment.
Get this on a production ready server.

Deploy this microservice to AWS.

Add directions for DB setup in development.

Deploy DB to AWS.

Separate model and schema to its own directory.

Write test cases for endpoints.

Add error handling.

Create auth service and make sure they are authenticated before they can use these endpoints.

Add config service so other services know what config to use.



