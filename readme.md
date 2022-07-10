# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Install [Docker](https://www.docker.com/).

You can verify Docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`.

Run `docker-compose up` from the project root directory to load Anythink's backend and frontend.

If Docker is working correctly, the backend should be running and able to connect to your local database. Point your browser [here](http://localhost:3000/api/ping) to verity everything is working properly.

If everything is working properly, you’ll be able to create a new user [here](http://localhost:3001/register).
