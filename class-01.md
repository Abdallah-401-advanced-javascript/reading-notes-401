# Read 01 ~ Node Ecosystem, TDD, CI/CD
> By Abdallah obaid

**NAME**     | **URL**
------------ | -------------
Home         | [Home](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/).
 Prep        | [Prep: Engineering Topics](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/Prep).
 Read 01     | [Node Ecosystem, TDD, CI/CD](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-01).
 Read 02     | [Classes, Inheritance, Functional](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-02).
 Read 03     | [Data Modeling & NoSQL Databases](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-03).
 Read 04     | [Advanced Mongo/Mongoose](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-04).
 Read 05     | [Linked Lists](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-05).
 Read 06     | [HTTP and REST](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-06).
 Read 07     | [Express](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-07).
 Read 08     | [Express Routing & Connected API](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-08).
 Read 09     | [API Server](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-09).
 Read 10     | [Stacks and Queues](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-10).
 Read 11     | [Authentication](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-11).
 Read 12     | [OAuth](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-12).
 Read 13     | [Bearer Authorization](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-13).
 Read 14     | [Access Control (ACL)](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-14).
 Read 15     | [Trees](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-15).
 Read 16     | [Event Driven Applications](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-16).

 
----------------------------------
# Node Ecosystem, TDD, CI/CD:-
----------------------------------
 ## Ecosystem:
   Managed lifecycle and dependency injection for your application components

 ## Node.js:
   * IS a **free open source server environment**, runs on **various platforms** (Windows, Linux, Unix, Mac OS X, etc.) and uses **JavaScript** on the **server**.
   * Node.js uses asynchronous programming.
   $ Node.js can generate dynamic page content.
   * Node.js can create, open, read, write, delete, and close files on the server.
   * Node.js can collect form data.
   * Node.js can add, delete, modify data in your database.
   * Node.js files contain tasks that will be executed on certain events.

 ## Package:
   * A package is a file or directory that is described by a package.json file. A package must contain a package.json file in order to be published to the npm registry.
 ## Module:
   * A module is any file or directory in the node_modules directory that can be loaded by the Node.js require() function.
   * Since modules are not required to have a **package.json** file, **not all modules are packages. Only modules that have a package.json file are also packages**.
   * var superagent = require('superagent')
 ## V8 JavaScript Engine:
   * V8 is Google's open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node. js, among others.
   * It's the thing that takes our JavaScript and executes it while browsing with Chrome.
   * V8 provides the runtime environment in which JavaScript executes.
 ## node package manager (npm):
   * npm is the world’s largest software registry.
   * Developers can share their reusable code using this large registry.
 ## A Node.js server:
   * Provides the mechanisms for connecting to a service and sending/receiving data. This is done through TCP or UDP connections. This allows developers to create their own servers using these protocols or the protocols built upon them (like HTTP).
   * var http = require('http');
   * var express = require('express');
 ## NODE.ENV:
   * Is an environment variable made popular by the express webserver framework. When a node application is run, it can check the value of the environment variable and do different things based on the value. NODE_ENV specifically is used (by convention) to state whether a particular environment is a production or a development environment. A common use-case is running additional debugging or logging code if running in a development environment.
 ## Compiler:
   * Is a translator which transforms source language (high-level language) into object language (machine language).
 ## Interpreter:
   * Interpreter is a program which imitates the execution of programs written in a source language.

----------------------------------
# Reading, Research, and Discussion:-
----------------------------------
> 1. Why would you want to run JavaScript code outside of a browser?
   * Running JavaScript inside a browser means you are interacting with Web UI (HTML and CSS components) which is displayed on a user's screen. Running JavaScript without/outside a browser means you are using node. js technology to execute your JavaScript code. This type of usage of javascript typically refers to backend programming where your javascript code will interact with your database and can be used to create RESTful APIs.
> 2. What is the difference between a module and a package?
   * Since modules are not required to have a package.json file, not all modules are packages. Only modules that have a package.json file are also packages.

> 3. What does the node package manager do?
   *Store the user's node packaging in their registry, and allow other users to reuse the public one
> 4. Provide code snippets showing 3 different ways to export a function from a node module.
   * Export Object:
     // Log.js
     module.exports.log = function (msg) { 
     console.log(msg);
     };
     // app.js
     var msg = require('./Log.js');
     msg.log('Hello World');
     // Run and see the output in command prompt as shown below
     `C:\> node app.js`
     `Hello World`

   * Export Function:
     // Log.js
     module.exports = function (msg) { 
     console.log(msg);
     };
     // app.js
     var msg = require('./Log.js');
     msg('Hello World');
     // Terminal
     `C:\> node app.js`
     `Hello World`

   * Export function as a class:
     // person.js
     module.exports = function (firstName, lastName) {
     this.firstName = firstName;
     this.lastName = lastName;
     this.fullName = function () { 
         return this.firstName + ' ' + this.lastName;
     }
     }
     // app.js
     var person = require('./Person.js');
     var person1 = new person('James', 'Bond');
     console.log(person1.fullName());
     // Run the above example as below in terminal
     `C:\> node app.js`
     `James Bond`
   

 ![npm](./Img/npm.png)