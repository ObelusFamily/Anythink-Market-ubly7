# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Hi there! Welcome to Anythink! Let's help you set your environment up!

Follow these steps, it should take a short while-

1. We need docker which will make it easier for us to run things locally. So,
download and install docker. 

2. After successfully installing docker, run the following commands in your terminal-
	- docker -v
	- docker-compose-v

3. Then run docker-compose-up from the project root directory to load Anythink's frontend and backend.

4. If docker is working correctly, backend should be running and able to connect to your local database. Test this, by pointing your browser to http://localhost:3000/api/ping

5. Once backend is running successflly, check the frontend and make sure it is connected to the backend. Point your browser to http://localhost:3001/register. Create a new account.

6. Your environment is now ready! Run your scripts in the next quests on one of the containers created docker-compose up. You can also use docker exec to run commands on a running container. All the best.
