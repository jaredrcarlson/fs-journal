# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > Synchronos code executes tasks sequentially (one after the other), whereas Asynchronous code allows multiple tasks to be initiated without waiting for each one to finish before moving to the next.

02. What is an event listener?

  > It's a procedure in JavaScript that waits for a particular event to occur (ex: mouse click or hover) and is commonly used to trigger an action (ex: execute a function).

03. What does *REST* stand for, and in simple terms what does it mean??

  > REST stands for REpresentational State Transfer. The representational piece refers to the way data or services are represented as URLs. REST relies on stateless client-server communication so each client request (HTTP > GET, POST, PUT, DELETE) contains all the info needed for the server to understand and process that request.

04. What is a callback / higher order function?

  > A callback is a function that is passed as an argument to another function. The purpose is to allow the receiving function to execute the callback function at a certain point or in response to a specific event. For example, the function passed into JavaScript's `setTimeout` function is a callback function.

05. What is a `promise`? How do you capture an error from a `promise`?

  > A JavaScript Promise is an object that represents the eventual completion or failure of an asynchronous operation and its resulting value. Promises provide a way to handle asynchronous operations in a more structured manner so the resulting code is easier to read and write.

06. Name three processes used to make requests over `HTTP`?

  > DNS resolution, TCP handshake, and HTTP request/response. The most common HTTP requests/methods are: GET, POST, PUT, and DELETE.

07. What does the `API` acronym stand for?

  > Application Programming Interface

08. What must you do in order to `await` a promise inside of a function?

  > Your function definition needs to start with the keyword 'async'.

09. What is the purpose of encapsulation in programming?

  > Encapsulation restricts access to data members and/or data methods within an object. Encapsulation is used to protect the state values within an object.

10. What is `HTTP` response code for a successful request?

  > 200 "OK" means the HTTP request was successful. 

11. What is a 400 error?

  > 400 "Bad Request" - The server can't return a valid response due to a CLIENT-SIDE error. (ex: bad URLs, large file size, deceptive request routing, ...)
