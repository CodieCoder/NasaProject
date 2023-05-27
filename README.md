# NASA Mission Control Project

A NASA Mission Control to create rocket launch, view upcoming launch and view past launches.

## Installation

1. You need to install Node js.
2. Install Mongo DB locally or use the MongoDB online cluster.
3. Create a `server/.env` file with a `MONGO_URL` property set to your MongoDB connection string.
4. In your terminal, run: `npm i` to install the project's node dependencies

## Running the Project

1. In your terminal, run: `npm run deploy`
2. In your browser navigate to [localhost:8000](http://localhost:8000) to start launching rockets!!!!


## Using Docker

1. You need to have the latest version of Docker installed
2. To build, in your terminal, run `docker build -t nasa-project .`
3. To run the project, in your terminal, run`docker run -it -p 8000:8000 nasa-project`

## Running the Tests

To run any automated tests, run `npm test`. This will: 
* Run all the client-side tests: `npm test --prefix client`
* Run all the server-side tests: `npm test --prefix server` 
