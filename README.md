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
git clone --depth 1 https://github.com/bwks/1011ICT-Applied-Computing
```

## Useage

### Start environment
CD into the `1011ICT-Applied-Computing`

Run `bin/dev up`. Then in a web browser, browse to `localhost:8080`
and you should see a table with the data loaded from the `myDb.sql` file.

### PHP My Admin

You can also browse to `localhost:8081` and log in to the database with the `phpmyadmin` application.

#### Database Details

- Server: mysql
- User: user
- Password: test
- Database: myDb
