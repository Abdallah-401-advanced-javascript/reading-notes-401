# Read 36 ~ Application State with Redux
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

----------------------------------
 # Application State with Redux
----------------------------------
 ## Redux:
  * **Redux** is an open-source JavaScript library for managing application state. It is most commonly used with libraries such as React or Angular for building user interfaces.

 ## Redux Store:
  * **store** is where your application state is, well, stored. The store’s job is to identify the various reducers and middleware that need to be made available and used globally.
  * In the store, we declare what middleware we may need and the reducers that we’ll use to manage your state data.

 ## Redux Reducers:
  * **Reducers**:  hold and manage state.
  * Reducers typically manage just one part of the larger application state.
  * Identifies what todo when a certain action (e.g. INITIALIZE) is called.

 ## Redux Action:
  * Returns an action object with the action type to perform and the data to perform it with.
  * When your component wants to modify state, it “Dispatches” (calls) an action and sends whatever payload (data) it needs to, to the reducer.

 ##  Provider Wrapper:
  * The provider wrapper is a means that React uses to allow child components to have access to higher level context.


 
 ![React](./Img/Redux.gif)