# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Getting Started:

1. First clone [this repo](https://github.com/ObelusFamily/Anythink-Market-me6mo)
2. Download and install [Docker](https://github.com/ObelusFamily/Anythink-Market-me6mo)
3. Next open the repository in your IDE/Code Editor
4. Open your terminal (If you are using an editor like Webstorm or VS Code, there is an integrated terminal) and run the command ```bash docker-compose up```
5. To check if the backend is working point your browser to `http://localhost:3000/api/ping`
6. In a different terminal tab go to the frontend directory ```bash cd frontend/```
7. Install dependencies by running the following command ```bash Yarn```
8. Start the development server by running the following command ```bash yarn start```
9. To check if the frontend is working point your browser to `http://localhost:3001/register` and create a new user

Congratulations! You have successfully set up the tools that you will need to work with this project.
