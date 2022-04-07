# NASA Mission Control Project

My personal completed version of the NASA project from [Complete Node.js Developer: Zero to Mastery](https://academy.zerotomastery.io/p/learn-node-js?affcode=441520_1jw4f2ay).

Keep in mind that this code may be different from the original since it was made by me during course classes and not copied from the original repository.

## Getting Started

1. Ensure you have Node.js installed.
2. Create a free [Mongo Atlas](https://www.mongodb.com/atlas/database) database online or start a local MongoDB database.
3. Create a `server/.env` file with a `MONGO_URL` property set to your MongoDB connection string.
4. In the terminal, run: `npm install`, it should install all dependencies from both client and server altogether
5. In case you make changes in any file inside client folder, create a `client/.env` file with a `BUILD_PATH` property set to `server/public` folder before deploying your react app.

## Running the Project

1. In the terminal, run: `npm run deploy`
2. Browse to the mission control frontend at [localhost:8000](http://localhost:8000) and schedule an interstellar launch!

## Running the Tests

To run any automated tests, run `npm test`. This will: 
* Run all the client-side tests: `npm test --prefix client`
* Run all the server-side tests: `npm test --prefix server` 