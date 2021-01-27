# How to set up a CI/CD Pipeline for a node.js app with Github Actions
We are going to build a simple NodeJS app and host it. This guide will show you how to config and work with Github Actions to deploy the NodeJS app to your server. 

Whenever you change something in code and push, Github will fire an event and will start to do the things we said. here we are going to install dependencies, run the test we wrote, if all tests are passed, Github action will deploy the app to the server.

Another bonus thing that we are going to do here is run Matrix builds. it means we run our tests on multiple NodeJS versions. (you can use Multiple Operating Systems as well). it will help us to confirm our app works on (multiple Operating Systems) and multiple NodeJS versions without an issue.

# Run server
$node app.js

# Unit testing
$npm test