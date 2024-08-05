# Nodejs CRUD with EJS


# Pre-requisites
- Install [Node.js](https://nodejs.org/en/)


# Getting started
- Clone the repository
```
git clone  <git lab template url> <project_name>
```
- Install dependencies
```
cd <project_name>
npm install
```
- Build and run the project
```
npm start
```
  Navigate to `http://localhost:3000`


## Project Structure
The folder structure of this app is explained below:

| Name | Description |
| ------------------------ | --------------------------------------------------------------------------------------------- |
| **dist**                 | Contains the distributable (or output) from your TypeScript build.                            |
| **node_modules**         | Contains all  npm dependencies                                                                |
| **src**                  | Contains  source code that will be compiled to the dist dir                                   |
| **configuration**        | Application configuration including environment-specific configs                                     |
| **src/controllers**      | Controllers define functions to serve various express routes.                                        |
| **src/lib**              | Common libraries to be used across your app.                                                         |
| **src/middlewares**      | Express middlewares which processes the incoming requests before handling them down to the routes    |
| **src/routes**           | Contain all express routes, separated by module/area of application                               |
| **src/models**           | Models define schemas that will be used in storing and retrieving data from Application database  |
| **src/monitoring**       | Prometheus metrics                                                                                |
| **src**/index.ts         | Entry point to express app                                                                        |
| package.json             | Contains npm dependencies as well as [build scripts](#what-if-a-library-isnt-on-definitelytyped)  | 
| tsconfig.json            | Config settings for compiling source code only written in TypeScript                              |
| tslint.json              | Config settings for TSLint code style checking                                                    |
