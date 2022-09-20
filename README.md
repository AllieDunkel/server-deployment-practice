# Notes

Importing and Exporting Modules

If one module exports a function or an object ...

// person.js
const person = {};

person.walk = function() {
  return 'walking';
}

module.exports = person;
Another module can import and use that function or object

const human = require('./person.js'))
console.log( human.walk() );  // prints 'walking'
CI/CD - Continuous Integration and Deployment
In your lab today, you'll be doing a full "professional" deployment using 2 branches, PR's, and a continuous process to get your code deployed.

You will repeat this process for every server based lab moving forward. Keep these notes (and the lab steps) handy for future reference

## URL's

Heroku applications: https://git.heroku.com/allie-server-deploy-dev.git 

Github actions:

Pull request: https://github.com/AllieDunkel/server-deployment-practice/pull/1 

## Drawings