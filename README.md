Next js follow SSR while Reactjs is CSR

manages server, database and application logic



Less users or interactivity, static websites -> SSR because whole document has to rebuild by server and then sent back.


Node.js is a runtime enviorment that can run server-side javascript applications.

Express is a server-side javascript web framework that runs on top of node.js.


Express.js is a framework running on top of node.js that handles HTTP requests made to
a web server.

A runtime behaves similarly to a mini operating system that provides the resources necessary
for an application to run.
The runtime is the infrastructure that supports the execution of a codebase.
It is the hardware and software environment in which an application gets executed.
Node.js is an example of a backend runtime environment.

Load refers to the number of concurrent users, the number of transactions, and the amount
of data transferred back and forth between the clients and servers.
Web applications should be scalable.
Scalability is the application’s ability to dynamically handle the load as it grows or shrinks
without it affecting the application’s performance.


node.js Event-Driven, Asynchronous, Non-Blocking, Single-Threaded:


While Node.js provides packages to create a server, the Express framework simplifies the process of creating APIs and endpoints. An API endpoint is a specific point of entry for a request from the client to the server.

Modules - encapsulated js code -> serves a single purpose

calling a module -> import() or require() depending on specification

packages - directory containing one or more modules.

Module specifications are conventions and standards used to create packages.

![Screenshot](https://github.com/Ekanshthegreat/IBMCourse/raw/main/1.png)

asynchronous (import) runs faster

require() with commonjs
```bash
module.exports = 'hello programmers';



let msg = require('./message.js');
``` 

Using ES module

```bash
const a = 1;
export {a as "myvalue"};

import {myvalue} from module.mjs;
```

When the user selects an option in the web page, it triggers business logic written as
a JavaScript application.
The JavaScript application sends a web service request using JavaScript Object Notation (JSON)
over hypertext transfer protocol (HTTP).
On the server, a Representational State Transfer (REST) web service intercepts the call.
