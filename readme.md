# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the
db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md)
and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug
branch and add `@vanessa-cooper` as reviewer.

## First setup

- Before running the project, we need to install Docker. Can be installed
following [this tutorial](https://docs.docker.com/get-docker/).
- Once docker is installed, verify if the docker is running by typing `docker -v` and `docker-compose -v`
- Now go to the root folder of the project and type `docker compose up`
- Once the setup is complete, go to `http://localhost:3000/api/ping` to check if the backend is up.
- We also need to check frontend by going to `http://localhost:3001/register` and creating an account there.
- That's it! You have successfully setup frontend and backend of the project

We can run scripts within the running container by execing into it. You can exec by `docker exec <container_name>` 