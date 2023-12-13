# README

# Local Setup

## Ruby
* Follow the instructions on Github to install [rbenv](https://github.com/rbenv/rbenv).
* Install ruby 3.2.2 using `rbenv install 3.2.2`.
* You might face an issue with `libyaml`, you can fix it by installing using `brew install libyaml`.

## Postgres
* Make sure you have docker installed and running.
* Start the postgres docker image using `docker-compose up -d`
* In the root of the project, run `rails db:create`

## Running
`rails s`

