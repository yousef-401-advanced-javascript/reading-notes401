# Classes, Inheritance, Functional Programming

## Name 3 advantages to Test Driven Development

- Development costs are cut.
- Quality is improved.
- Bugs are reduced.

## In what case would you need to use beforeEach() or afterEach() in a test suite?
run  before and after each test code

## What is one downside of Test Driven Development

- A challenge to learn
- Hard to apply to legacy code
- Lot's of misconceptions that keep programmers from learning it

## What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
the class has an constructor inside it that contain the properties and methods but Constructor/Prototype has the properties directly and the method delared out side of the constructor

## Name a use case for a static method
Static methods aren't called on instances of the class. Instead, they're called on the class itself. These are often utility functions, such as functions to create or clone objects

## Write an example of a Higher Order function and describe the use case it solves
const arr1 = [1, 2, 3];<br />
const arr2 = arr1.map(function(item) {<br />
  return item * 2;<br />
});<br />
console.log(arr2);<br />
using a function as an parameter in other function (map Higher-order function )

### Document the following Vocabulary Terms


**functional programming:** is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects. Functional programming is declarative rather than imperative, and application state flows through pure functions.<br />
**pure function:**  is a function where the return value is only determined by its input values, without observable side effects<br />
**higher-order function:** is a function that takes a function as an argument, or returns a function.<br />
**immutable state:** the data that you can't change it<br />
**object:**  unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. <br />
**object-oriented programming (OOP):** a programming paradigm that uses abstraction to create models based on the real world. It uses several techniques from previously established paradigms, including modularity, polymorphism, and encapsulation.<br />
**class:** are a special syntax for its prototypical inheritance model that is a comparable inheritance in class-based object oriented languages<br />
**prototype:**  is special type of enumerable object to which additional properties can be attached to it which will be shared across all the instances of it's constructor function.<br />
**super:** keyword is used to access and call functions on an object's parent.<br />
**inheritance:**  concept of one thing gaining the properties or behaviours of something else.<br />
**constructor:** method is a special method for creating and initializing an object created within a class<br />
**instance:** means a reference to an “object” created by “new” or the equivalent.<br />
**context:** is always the value of the this keyword which is a reference to the object that “owns” the currently executing code or the function where it’s looked at.<br />
**this:** 
**Test Driven Development (TDD):** is a software development process that relies on the repetition of a very short development cycle: requirements are turned into very specific test cases, then the code is improved so that the tests pass<br />
**Jest:** delightful JavaScript Testing Framework with a focus on simplicity
**Continuous Integration(CI):**  is the practice of merging all developers' working copies to a shared mainline several times a day<br />
**unit test:** is made to check against an individual unit in JavaScript, which typically breaks down to a function or library. The goal is to check every aspect of the function to make sure it all works properly for all cases<br />
