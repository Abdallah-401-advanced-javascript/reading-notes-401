# Classes, Inheritance, Functional
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
# Classes, Inheritance, Functional:-
----------------------------------
 ## Functional programming:
   *(often abbreviated FP) is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects.

 ## pure function :
   1- Always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program’s execution. It must only depend on its input arguments.
   2- Does not produce any observable side effects such as network requests, input and output devices, or data mutation.

 ## Higher-order functions::
   * Is a function that takes a function as an argument, or returns a function . Higher order function is in contrast to first order functions, which don't take a function as an argument or return a function as output.


 ## Immutable state :
   * Unchanging over time or unable to be changed,When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

 ## JavaScript object:
   * Is a standalone entity that holds multiple values in terms of properties and methods.

 ## Object-oriented programming:
   * Object-oriented programming (OOP) refers to a type of computer programming (software design) in which programmers define the data type of a data structure, and also the types of operations (functions) that can be applied to the data structure.In this way, the data structure becomes an object that includes both data and functions. In addition, programmers can create relationships between one object and another.

 ## class:
   * A JavaScript class is a type of function, but instead of using the keyword function to initiate it, we use the keyword class, and the properties are assigned inside a constructor() method.

 ## prototype:
   * Is an object (called a prototype object) that has a constructor property by default. The constructor property points back to the function on which prototype object is a property.

 ## Super:
   * The super keyword refers to the parent class. It is used to call the constructor of the parent class and to access the parent's properties and methods.

 ## Inheritance:
   * refers to an object's ability to access methods and other properties from another object. Objects can inherit things from other objects. Inheritance in JavaScript works through something called prototypes and this form of inheritance is often called prototypal inheritance.

 ## Constructor:
   * A constructor is a function that creates an instance of a class which is typically called an “object”. In JavaScript, a constructor gets called when you declare an object using the new keyword. The purpose of a constructor is to create an object and set values if there are any object properties present.

 ## Context :
   * Context is always the value of the this keyword which is a reference to the object that “owns” the currently executing code.   

 ## this :
   * keyword refers to the object it belongs to And It has different values depending on where it is used.

 ## TDD :
   * Test-driven development is a programming methodology with which one can tackle the design, implementation, and testing of units of code, and to some extent the expected functionality of a program.

 ## Jest :
   * jest is a JavaScript test runner, that is, a JavaScript library for creating, running, and structuring tests. Jest is distributed as an NPM package, you can install it in any JavaScript project. Jest is one of the most popular test runner these days and the default choice for Create React App.

  ## Continuous Integration (CI) :
   * practices used by developers all over the world to increase the quality of their software, and decrease the time to market for features and bug fixes.

 ## Unit testing :
   * Unit testing is the process of testing the implemented code at a module level. Unit testing allows you to ensure that your developed modules are meeting the requirements specified by the business document. These tests are written for every module as they are created. After every new module development, the entire suite of test cases is run to ensure that no existing modules are affected by the developed module.


----------------------------------
# Reading, Research, and Discussion:-
----------------------------------
>1. Name 3 advantages to Test Driven Development:
  * Writing the tests first requires you to really consider what do you want from the code.
  * You receive fast feedback.
  * TDD creates a detailed specification.
  * TDD reduces time spent on rework.

>2. In what case would you need to use beforeEach() or afterEach() in a test suite?
 * If you have some work you need to do repeatedly for many tests, you can use beforeEach and afterEach.

>3. What is one downside of Test Driven Development:
 * Is that if you really want to do TDD properly you will have to fail a lot before you succeed. Given how many software companies work (dollar per KLOC) you will eventually get fired.

>4. What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
* ES6 class basically does the work of defining a new object and appending functions to its prototype, ES5 Function constructors work and look the same but the main difference is observed when the developer uses the Inheritance property.

>5. Name a use case for a static method: 
class User {
  static staticMethod() {
    alert(this === User);
  }
}
User.staticMethod(); // true

>6. Write an example of a Higher Order function and describe the use case it solves: 
* The snippet below loops over an array and invokes a function on each item until it has reached the last item. The capability of taking a function that it can invoke is what makes it a higher order function: function prefixWordWithUnderscore(word) { return _${word} } const words = ['coffee', 'apple', 'orange', 'phone', 'starbucks'] const prefixedWords = words.map(prefixWordWithUnderscore) // result: ["_coffee", "_apple", "_orange", "_phone", "_starbucks"]
    

 ![npm](./Img/high.png)