# 01 - Only pure NodeJS modules

In this first chapter we will create the skeleton of our web server but with a particularity: the whole project will be
written with modules that are part of the NodeJS runtime, that is, without any external dependency.
NodeJS has a battery of modules included to perform many of the tasks that today are common today.

These modules are part of the core of NodeJS and are the ones that support others that we will use later.

## A minimal, basic and incomplete server

In this section we will create our first server and we will publish it locally.
The different sections that compose it will be included and then the complete code will be published to ensure that it is complete.

We start with a new file: `index.js` and we start writing code:

For this server we will need to include a single module, this is: `http`

`var http = require ('http');`

With this simple line we have inserted in our script the http protocol module.
The `require` function has a single module to include as a parameter.
