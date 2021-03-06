[![CircleCI](https://dl.circleci.com/status-badge/img/gh/Abdolla25/deploy-udagram/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/Abdolla25/deploy-udagram/tree/main)

# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.


#### Project Demo: [Frontend Demo](http://udagram-235373009437.s3-website-us-east-1.amazonaws.com/), [API Demo](http://udagram-api-dev.eba-tqm2tvae.us-east-1.elasticbeanstalk.com/)

### Project Infrastructure

This project is a compination of two applications using angular and express.

#### For more details and diagrams follow this [Link](docs/infrastructure.md).

### Main Project Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

#### For more information about frontend and backend dependencies use this [Link](docs/dependencies.md).

### Pipeline Process

In this project we have used CI/CD integration that triggers automaticly by GitHub using circleci.

follow this [Link](docs/pipeline.md) for more information.

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
