# Udacity - Hosting Udagram Fullstack Application

## Instructions

- The documentation folder attached in the project folder includes separate pages on different topics:
  1.  Infrastructure description.
  2.  App dependencies.
  3.  Pipeline process.
- This project require some prequesites and dependenscies to be installed.

---

## Usage

[(Back to top)](#table-of-contents)

You can Install this project to your PC using clone the repo to your github account then Download It as a ZIP File to your PC.

or Clone it using GIT `git clone` if you access it from GITHUB.

---

### Dependencies

```
- Node

- npm

- AWS CLI

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

---

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

#### Installation npm:

    • npm install .
    • npm run dev .
    • npm run start .

---

#### Ports:

    • Server port 3000.
    • Database port 5432.

---

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

## The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

---
