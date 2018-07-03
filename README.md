How to get the database up and running:

Based on: https://auth0.com/blog/sqlalchemy-orm-tutorial-for-python-developers/

docker run --name sqlalchemy-orm-psql \
    -e POSTGRES_PASSWORD=pass \
    -e POSTGRES_USER=usr \
    -e POSTGRES_DB=sqlalchemy \
    -p 5432:5432 \
    -d postgres
