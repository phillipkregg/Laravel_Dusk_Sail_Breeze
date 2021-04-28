# Laravel / Dusk / Breeze / Sail - Base Setup

This project uses Laravel Sail instead of a local PHP/MySQL environment or Valet.

Renaming the `.env.example` file to `.env` should get you the right DB host name and correct ports.

## Running Sail

You can get the docker image up and running by entering this command in the root of the directory:
`./vendor/bin/sail up`

To shut down the docker image:
`./vendor/bin/sail down`

## View project

Once Sail is running, the project can be viewed at just `localhost`

## View Database

Connect to the db while Sail is running with the default Sail credentials:
`username: sail`
`password: password`

## Run Integration Tests

`php artisan dusk`
