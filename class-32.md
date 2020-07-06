# Read 32 ~ Custom Hooks
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
 
----------------------------------
# Hooks API
----------------------------------

 ## Hooks:
  * **Hooks** are functions that let you “hook into” React state and lifecycle features from function components.
  * **Hooks** don't work inside classes.
  * **React Hooks are functions that let us hook into the React state and lifecycle features from function components.**
  * `useState()`Returns a stateVariable and setterFunction for you to use to manage state in a functional component.

 ## Custom Hooks:
  * **Custom hooks** allow you to create functionality that can be reused across different components.
  * Its name should always start with **use**
  * Extract duplicated logic from components, share common functionality, **But not state** and take advantage of useEffect lifecycle.
  * **Custom Hook doesn’t need to have a specific signature *unlike a React component*. We can decide what it takes as arguments, and what, if anything, it should return.**
  * Hooks do not render.

 ## Common use cases – make things DRY:
  1. Handle forms easily.
  2. Pre-fetch API data.
  3. Connect to services (like socket.io, Q, etc).
  

 ![React](./Img/React.jpg)