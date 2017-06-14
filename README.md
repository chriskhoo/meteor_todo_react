# meteor_todo_react
Todo tutorial on meteor (mongo, react)

This tutorial references : [official meteor-react tutorial](https://www.meteor.com/tutorials/react/creating-an-app)

It follows most of the instructions with the exception of changing `Meteor.userId()` to `this.userId` in `imports > api > tasks.js`. This facilitates testing of the task functions without stubbing a user. 

## Instructions
- To start application: meteor
- To start tests: meteor test --driver-package practicalmeteor:mocha
