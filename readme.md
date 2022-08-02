# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- For starters, we must install Docker before moving forward. To do that, a user can follow [this link](https://docs.docker.com/get-docker/), where there will be the option to select the appropriate os followed by step-by-step instructions on completing the installation.

- Upon installing, ensure Docker is ready to use by running the following commands in your terminal/CLI: '`docker -v`' and '`docker-compose -v`'. (The output should look something like this: '`Docker version ##.##.##, build 101b453`')

- After verifying that Docker is up to date and ready to use, `cd` into the cloned repo, and from the root directory run the command '`docker-compose up`'. If Docker is working as expected, this will fire up both the frontend and backend servers.

    - To test the backend visit [localhost:3000/api/ping](http://localhost:3000/api/ping)

    - To test the frontend visit [localhost:3001/register](http://localhost:3001/register) and create a new user before moving on.    

