# LAB - Class 16

## Project: AWS Cloud Servers

### Author: Branden Ge

### Problem Domain

This lab demonstrates how to deploy a simple server to AWS with EC2 and Elastic Beanstalk.

- [CI/CD GitHub Actions](https://github.com/brandenge/cloud-server/actions)
- [CLI Deployed](http://cloudserverclideploy-dev.us-east-2.elasticbeanstalk.com//)
- [GUI Deployed](http://cloudserverguideploy-env.eba-tujnwzhz.us-east-2.elasticbeanstalk.com//)

### Setup

- Add `.env` file with a `PORT` variable set to a port number as shown in the `.envsample`.

#### Running the app

- `npm start` or `nodemon` (if you have nodemon) to start the application.

#### Features / Routes

- GET : `/` - root
- GET : `/bad` - designated bad route that always responds with a 500 Internal Server Error.
- GET : `*` - catch-all route which always responds with a 404 Not Found error.

#### Tests

- `npm test` to run tests

#### UML Diagram

![UML Diagram](uml1.png)

Diagram created with [InVision](https://www.invisionapp.com/)

#### Credits: [Demo code from Ryan Gallaway at Code Fellows](https://github.com/codefellows/seattle-code-javascript-401d48/tree/main/class-01/inclass-demo)
