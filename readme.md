# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

* Go ahead and create your own codespace , I'll wait
    (No need to change anything in the default options, just click on the Create codespace button and wait for it to boot)
* Once your codespace is up and running. You can now run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.
* Once docker-compose finishes loading up, the backend should be running and able to connect to the database.
* After the server is up, make sure you test it by pointing your browser to the '<url>/api/ping'
* Now, it’s time to check the frontend and make sure it’s connected to the backend.
* If everything is working properly, you’ll be able to create a new user on '<url>/register'
* Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.