# Read 39 ~ Redux - Additional Topics
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
 Read 17     | [TCP Servers](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-17). 
 Read 18     | [Socket.io](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-18).
 Read 19     | [Message Queues](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-19).
 Read 26     | [Component Based UI](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-26). 
 Read 27     | [React Testing and Deployment](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-27).  
 Read 28     | [Props and State](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-28). 
 Read 29     | [Component Composition](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-29).
 Read 30     | [Hash Tables](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-30).
 Read 31     | [Hooks API](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-31). 
 Read 32     | [Custom Hooks](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-32). 
 Read 33     | [Context API](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-33).  
 Read 34     | [`<Login />` and `<Auth />`](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-34).  
 Read 35     | [Graphs](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-35).   
 Read 36     | [Application State with Redux](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-36).    
 Read 37     | [Combined Reducers](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-37).  
 Read 38     | [Asynchronous Actions](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-38).   
 Read 39     | [Redux - Additional Topics](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-39).   
----------------------------------
 # Asynchronous Actions
----------------------------------
 ## Redux Toolkit "RTK":
  * To add the package `npm install @reduxjs/toolkit`.
  * Includes utilities to simplify common use cases like store setup, creating reducers, immutable update logic, and more.
  * **Toolkit** specifies a few different means of building a reducer and action set that work well together and are easier to understand and integrate.
  * We can replace the plain Redux createStore function with RTK's configureStore. This will automatically set up the Redux DevTools Extension for us.

 ## Ducks: Redux Reducer Bundles:
  * Ducks is a modular pattern that collocates actions, action types and reducers.
  * The original ducks modular approach is a nice simplification for redux and offers a structured way of adding each new feature in your app.
 
 ![React](./Img/Redux.gif)