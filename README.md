# Laradock Makefile (custom)

Makefile with some useful commands for [Laradock](http://laradock.io/)

## Installation

Copy the `Makefile` from this repo to your project root.

You can do this with:

`wget https://raw.githubusercontent.com/bazavlukd/laradock-makefile/master/Makefile`

Download Laradock:

`make install-laradock`

Run all containers:

`make up`

Run initial scripts to build the project

`make initial-build`

Enjoy =)

## Commands available
* `up` - run all containers
* `down` - stop all containers
* `log` - show Laravel log
* `docker-log` - show docker log
* `join-workspace` - get into workspace container
* `join-php` - get into php container
* `join-db` - get into db container and login into postgres
* `npm-install` - install js dependencies
* `build-js` - run npm build
* `build-js-production` - run npm build for production
* `watch-js` - run npm watch
* `key-generate` - generate key for laravel
* `new` - asks you to enter command and coomand name and create it
* `new-migration` - asks you to enter migration name and create it (requires sudo since it created inside a container)
* `run-migrations` - run artisan migrate
* `run-seeds` - run artisan db:seed
* `composer-install` - install php dependencies
* `test` - run test with phpunit
* `install-laradock` - install laradock
* `initial-build` - run initial scripts to build the project
* `queue-flush` - flush redis queue
* `horizon` - run laravel horizon queue
* `up-ngrok` - run ngrok to expose nginx webserver on port 80
