# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install [Docker](https://docs.docker.com/get-docker/). Once docker is installed you can verify this by running the following commands in the CLI, `docker -v` and `docker-compose -v`
2. Run `docker-compose up` from within the project root directory to start up the Anythink's backend, frontend and database
3. Verify the backend is running by hitting `http://localhost:3000/api/ping`
4. Verify the frontend is opening `http://localhost:3001/register` and creating a new user
5. You are all done!