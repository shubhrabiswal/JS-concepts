### 1. How does Node.js work?
Node.js is a platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. 
Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications 
that run across distributed devices. Node.js is an open source, cross-platform runtime environment for developing server-side and networking applications. 

### 2. What is non-blocking I/O ?
Node treats your event-cycle as a waiter at a restaurant. When it delivers a request to it,
 it frees it right away. Meaning that the waiter doesn't have to wait till the food is ready to take the next order. Think of a restaurant where each customer will be served by one separate waiter.15
 
### 3. Explain callback in Node.js.
 Callback is an asynchronous equivalent for a function. A callback function is called at the completion of a given task. Node makes heavy use of callbacks. All the APIs of Node are written in such a way that they support callbacks.
 (handle err res)
 
 
 Why is Node.js Single-threaded?
 
 Node.js was created explicitly as an experiment in async processing. The theory was that doing async processing on a single thread could provide more performance and scalability under typical web loads than the typical thread-based implementation.
 What is NPM?
Explain the concept of middleware in Node.js.
What are the different types of HTTP requests?
-->get put post patch

Why is Node.js preferred over other backend technologies like Java and PHP?

NodeJs syntax is more easy.
NodeJs is a runtime library and environment which is cross-platform and used for creating running JavaScript applications outside the browser.
NodeJs is single-threaded.
NodeJs is building fast and scalable applications.
Non-blocking I/O paradigm
Easy and fast coding

What does event-driven programming mean?
Event-driven programming is a programming paradigm in which the flow of program execution is determined by events - for example a user action such as a mouse click, key press, or a message from the operating system or another program. An event-driven application is designed to detect events as they occur, and then deal with them using an appropriate event-handling procedure. The idea is an extension of interrupt-driven programming of the kind found in early command-line environments such as DOS, and in embedded systems (where the application is implemented as firmware).

What is an Event Loop in Node.js?

Event loop is an endless loop, which waits for tasks, executes them and then sleeps until it receives more tasks.
The event loop executes tasks from the event queue only when the call stack is empty i.e. there is no ongoing task.
The event loop allows us to use callbacks and promises.
The event loop executes the tasks starting from the oldest first.


What are the two types of API functions in Node.js?

API stands for Application Programming Interface. It consists of various communication protocols and subroutines that can be used by programs for inter-communication. There are various types of APIs available such as WEB APIs, LOCAL APIs, PROGRAM APIs, etcetera. They are one of the most efficient and reliable ways to deliver output.

Types of API functions in Node.js:

Asynchronous, Non-blocking functions
Synchronous, Blocking functions
Asynchronous, Non-blocking functions: As the name suggests, these functions operate asynchronously. What it means is that when Node.js will make a request for data to the API, it will not get blocked till the data is received. Instead, it will continue to move to the next API after calling it, and a notification mechanism from a Node.js event will respond to the server for the previous API call. To put it in layman’s terms, these functions allow working further while the request is being handled. Example: Emails, online forums

Synchronous, Blocking functions: Contrary to asynchronous functions, synchronous functions act as blocking functions. What it means is that these functions will make the calling system wait for a response. Thus, when a system uses synchronous APIs, it expects to get immediate data when requests are made. These types of APIs are used where availability and connectivity are high and low latency is expected. To put it in layman’s terms, the application will request and wait for a response until the value is returned. Example: Instant messaging, video meetings

What is the purpose of module.exports?

What is REPL in Node.js?
The Node. js Read-Eval-Print-Loop (REPL) is an interactive shell that processes Node. js expressions. The shell reads JavaScript code the user enters, evaluates the result of interpreting the line of code, prints the result to the user, and loops until the user signals to quit. The REPL is bundled with with every Node.

What is piping in Node.js?

Pipes can be used to connect multiple streams together. One of the most common example is to pipe the read and write stream together for the transfer of data from one file to the other. 

What is the buffer class in NOde.js?
The Buffer class in Node. js is designed to handle raw binary data. Each buffer corresponds to some raw memory allocated outside V8. Buffers act somewhat like arrays of integers, but aren't resizable and have a whole bunch of methods specifically for binary data.
