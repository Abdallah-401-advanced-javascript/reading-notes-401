# Read 33 ~ Context API
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
 
----------------------------------
# Context API
----------------------------------

 ## Context:
  * Allows us to pass **data**, **state** and **functions** from Provider/Consumer . 
  * **Context** provides a way to pass data through the component tree without having to pass props down manually at every level.
  * **Context** provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.
  * **Context** is designed to share data that can be considered **global** for a tree of React components, such as the **current authenticated user**, **theme**, or **preferred language**.
  * **Context** is primarily used when some data needs to be accessible by many components at different nesting levels.
  * If you only want to avoid passing some props through many levels, **component composition** is often a simpler solution than **context**.

 
 ![React](./Img/React.jpg)