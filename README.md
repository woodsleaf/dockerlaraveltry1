# dockerlaraveltry1
on now i can solve how add laravel files in src without install in local machine php

and maybe it cause not add accss to
http: //127.0.0.1:8080

## Create

docker-compose build

## Start

`docker-compose up -d`

Docker will create our laravel network and then create the three containers we’ve specified in the services section of our docker-compose.yml file. If you’re curious about the -d flag, it stands for detached and keeps the containers running after all of their commands have processed. Otherwise, Docker would stop them as soon as they’ve finished their initialization. Pretty pointless for a web server!

## Stop

`docker-compose down`

### [Source](https://dev.to/aschmelyun/the-beauty-of-docker-for-local-laravel-development-13c0)