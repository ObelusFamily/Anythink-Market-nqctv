# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## Initial setup

1. If running on Mac, install Docker desktop to ensure you have the lastest version along with the most up-to-date CLI tools. Otherwise, visit the Docker documentation [here](https://docs.docker.com/docker-for-mac/install/) and follow the instructions.

1. Make sure you have Ruby 2.7.5 installed. Run `ruby -v` to check.
If not installed, use your package manager of choice to install it.
Then, open the repo in your editor.

1. `cd` into the `/backend` folder and run `bundle install`

1. Then, run `docker-compose up` to start the app.

1. You can now access the app at [`http://localhost:3000/api/ping`](http://localhost:3000/api/ping).

1. If the app is not working, you can stop the server by running `docker-compose down` or typing `ctrl + c` in the terminal.
