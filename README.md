# NASA Mission Control Project

My personal completed version of the NASA project from [Complete Node.js Developer: Zero to Mastery](https://academy.zerotomastery.io/p/learn-node-js?affcode=441520_1jw4f2ay).

Keep in mind that this code may be different from the original since it was made by me during course classes and not copied from the original repository.

## Getting Started

1. Ensure you have Node.js installed.
2. Create a free [Mongo Atlas](https://www.mongodb.com/atlas/database) database online or start a local MongoDB database.
3. Create a `server/.env` file with a `MONGO_URL` property set to your MongoDB connection string.
4. Create a `client/.env` file with a `BUILD_PATH` property set to `server/public` folder before deploying your react app.
5. In the terminal, run: `npm install`, it should install all dependencies from both client and server altogether

## Running the Project

1. In the terminal, run: `npm run deploy`
2. Browse to the mission control frontend at [localhost:8000](http://localhost:8000) and schedule an interstellar launch!

## Docker

1. Ensure you have the latest version of Docker installed
2. Run `docker build -t nasa-project .`
3. Run `docker run -it -p 8000:8000 nasa-project`

## Running the Tests

To run any automated tests, run `npm test`. This will: 
* Run all the client-side tests: `npm test --prefix client`
* Run all the server-side tests: `npm test --prefix server` 