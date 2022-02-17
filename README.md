
<<<<<<< HEAD
[![Manar-Mansour](https://circleci.com/gh/Manar-Mansour/aws-circleci-project.svg?style=svg)](https://app.circleci.com/pipelines/github/Manar-Mansour/aws-circleci-project/20/workflows/8c55567f-864f-43eb-b347-b0969bb49d52/jobs/26) 
=======
[![Manar-Mansour](https://circleci.com/gh/Manar-Mansour/aws-circleci-project.svg?style=svg)](https://app.circleci.com/pipelines/github/Manar-Mansour/aws-circleci-project/20/workflows/8c55567f-864f-43eb-b347-b0969bb49d52/jobs/26)
>>>>>>> 2621eec09c11a1477842a00f9b4046cf7611f7b4

# Udagram

The udagram application is a simple application that includes all the major components of a Full-Stack web application. I deployed this application to AWS as part of the Udacity Advanced full stack web development Nanodegree. I also used CircleCI for continuous integration and deployment (CI/CD). 
Link to the app: http://udagram-manar.s3-website-us-east-1.amazonaws.com 

## Getting Started

1. Clone this repo locally into the location of your choice.
2. Move the content of the udagram folder at the root of the repository as this will become the main content of the project.
3. Open a terminal and navigate to the root of the repo (udagram).
4. follow the instructions in the installation step

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres.
2. In AWS, provision a s3 bucket for hosting the uploaded files. 
3. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
4. Navigate to udagram-api folder `cd udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
5. Without closing the terminal in step 4, navigate to the udagram-frontend `cd udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. Navigate to the root folder of the project using `cd udagram` if you are not already inside it.
2. `npm run backend:test`
3. `npm run frontend:test`
4. `npm run e2e`

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
