# python-web-api-flask-ssl-mysql-pop

## Description
Creates an api of `pop` for a flask project.
Has the ability to query by parameters.
If path is not found, will default to 404 error.
Uses self-signed ssl.

## Tech stack
- python
- flask
- mysql

## Docker stack
- python:latest
- mariadb:latest

## To run
`sudo ./install.sh -u`
- Endpoint
  - [Availble](https://localhost/pop)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
- https://stackoverflow.com/questions/27766794/switching-from-sqlite-to-mysql-with-flask-sqlalchemy
- [Basic auth setup](https://medium.com/tek-society/how-to-secure-your-python-flask-routes-with-basic-auth-in-5-minutes-6e3cea1448a4)
