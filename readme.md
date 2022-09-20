# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker

   ```bash
   docker -v
   docker-compose -v
   ```

2. Run `docker-compose up` from the project root directory.
3. Check backend by going to [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
4. Check frontend by creating a new user via [http://localhost:3001/register](http://localhost:3001/register)
