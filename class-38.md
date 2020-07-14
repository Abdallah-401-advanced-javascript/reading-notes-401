# Read 38 ~ Asynchronous Actions
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
 Read 38     | [Combined Reducers](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-38).   

----------------------------------
 # Asynchronous Actions
----------------------------------
 ## Thunking for Data:
  * **Thunk**is middleware allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met.
  * Using Redux actions to connect to remote APIs via Thunk Middleware.
  * **Thunk** will inspects every dispatched action and then either lets it go through (in the case of a normal action that returns an object) or it processes the function and then dispatches what that function returns.
  * In Redux, middleware is implemented as a curried function that ultimately evaluates the action and determines whether it’s a function or not. If so, it gets invoked with the store’s dispatch() and getState() methods. Otherwise (a normal action creator), it simply runs your action.
  * **Thunk** provides more stability and error checking for us.
 
 ![React](./Img/Redux.gif)