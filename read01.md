# Node Ecosystem, TDD,CI/CD
### why would you want to run javascript code outside of a browser?
originally you were not supposed to run javascript outside a browser because it's created to make HTML pages more interactive.
now it's used for doing much more things than that , it's even used for server-side programming.To do so you often need to run programs using the console.since javascript was only run by the browser in HTML documents,Node.js was created.
Node.js allows you to write programs in JavaScript which can be run outside the browser.
### What is the difference between a module and a package?
**A package:** is a file or directory that is described by a package.json file. A package must contain a package.json file in order to be published to the npm registry.
**A module** is any file or directory in the node_modules directory that can be loaded by the Node.js require() function.
To be loaded by the Node.js require() function, a module must be one of the following:

- A folder with a package.json file containing a "main" field.
- A folder with an index.js file in it.
- A JavaScript file.
**Note:** Since modules are not required to have a package.json file, not all modules are packages. Only modules that have a package.json file are also packages.
### What does the node package manager do?
Node Package Manager (NPM) is a command line tool that installs, updates or uninstalls Node.js packages in your application. It is also an online repository for open-source Node.js packages. The node community around the world creates useful modules and publishes them as packages in this repository.
### export a function from a node module by 3 ways:
- **Export Literals:**(module.exports = 'anything'or exports = 'anything')
then in the other file use require(the path for the file that has an exported things)(let hi = require(./path)it will return the value)
- **Export Object:**(module.export.thename('any thing'))
then in the other file use require(the path for the file that has an exported things)(let hi = require(./path)it will return an object that contain functions  or values )<br />
hi.thename =>will return the value
- **Export Function:**modile.exports = function)
then in the other file use require(the path for the file that has an exported things)(let hi = require(./path)it will return the function)
#### ecosystem:
is used to describe the community around a software component, library, or tool.
#### Node.js:
is an open-source server side runtime environment built on Chrome's V8 JavaScript engine. It provides an event driven, non-blocking (asynchronous) I/O and cross-platform runtime environment for building highly scalable server-side application using JavaScript.
#### v8 engine
V8 is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node.js, among others.
#### module:
Module in Node.js is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node.js application.
#### package:
is one or more modules (libraries) grouped (or packaged) together. These are commonly used by other packages or a project of your own
#### node package manager (npm):
npm is the world’s largest software registry. Open source developers from every continent use npm to share and borrow packages, and many organizations use npm to manage private development as well.
#### server:
is a computer program or a device that provides functionality for other programs or devices, called "clients"
#### environment:
Environment variables are a fundamental part of developing with Node.js, allowing your app to behave differently based on the environment you want them to run in.
#### interpreter:
used to convert a program written in a high-level language into machine code understood by computers
**the features:**
- Translates program one statement at a time.
- It takes less amount of time to analyze the source code but the overall execution time is slower.
- Continues translating the program until the first error is met, in which case it stops. Hence debugging is easy.
#### compiler:
used to convert a program written in a high-level language into machine code understood by computers.
**the features:**
- Scans the entire program and translates it as a whole into machine code.
- Scans the entire program and translates it as a whole into machine code.
- It generates the error message only after scanning the whole program. Hence debugging is comparatively hard.




