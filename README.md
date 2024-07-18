# XAMPP Dockerized Replacement

I am using this Docker setup in my university course 1011ICT Applied Computing
instead of using XAMPP that is used in the university course because.

Initial configuration was taken from [here](https://gist.github.com/jcavat/2ed51c6371b9b488d6a940ba1049189b)

## Requirements

- Docker and Docker Compose

## Setup

Clone this repository without the history so you can 
check it into your own git repo.

```
git clone --depth 1 git@github.com:bwks/docker-xampp.git
```

## Usage

### Overview
CD into the `docker-xampp` directory.

There is a `dev` script in the `bin/` directory that 
can be used to interact with the environment.

### Start Environment
Run the `bin/dev up` command. Then in a web browser, browse to `localhost:8080`
and you should see a table with the data loaded from the `myDb.sql` file.

### Stop Environment 
Run the `bin/dev down` command.

## PHP My Admin

You can browse to `http://localhost:8081` and log in to the database using the `phpmyadmin` application.

### Database Details

- Server: mysql
- User: user
- Password: test
- Database: myDb
