# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. install docker - https://docs.docker.com/get-docker/
2.verify docker is running
    $ docker -v
    $ docker-compose -v
3.From the root directory run $ docker-compose up
    check that it is working by pointing your browser to http://localhost:3000/api/ping

--Just make sure that you run all scripts in the next quests on one of the containers created by  $ docker-compose up.  Also, you can use $ docker exec. to run commands on a running container.