# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1) Install Docker: [link](https://docs.docker.com/get-docker/)
2) Clone the repo
3) Run `docker-compose up` in the repo directory
4) Visit `http://localhost:3000/api/ping` to test the routes
5) Visit `http://localhost:3001/register` to create a new user account
