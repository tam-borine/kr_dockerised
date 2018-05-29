This directory allows you to create a [Docker](https://www.docker.com/) image of Airbnb's [Knowledge Repository](https://github.com/airbnb/knowledge-repo).

To create the image, run `docker build . -e SQLALCHEMY_DATABASE_URI=some_sql_db_uri`

If you don't have Docker installed, [get it here](https://docs.docker.com/install/).