# Enrollment

It's an enrollment tool.. wheee!

## Installation
For first use run, just to be sure
  $npm install

To start the app
  $npm start
Because then it wil run $nodemon app.js instead of $node app.js. See packages for more information.

### Installed Packages

####Nodemon
For use during development of a node.js based application.

nodemon will watch the files in the directory that nodemon was started, and if they change, it will automatically restart your node application.

nodemon does not require any changes to your code or method of development. nodemon simply wraps your node application and keeps an eye on any files that have changed. Remember that nodemon is a replacement wrapper for node, think of it as replacing the word "node" on the command line when you run your script.
[https://github.com/remy/nodemon](https://github.com/remy/nodemon)

  // installation for global
  npm install -g nodemon

  // for local add this to package.json
  "scripts": {
    "start": "nodemon app.js"
  },
  "devDependencies": {
    "nodemon": "*"
  }
  
  // usage
  nodemon app.js localhost 8080
