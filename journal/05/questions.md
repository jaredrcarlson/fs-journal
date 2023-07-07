# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > CRUD stands for Create, Read, Update, Delete.

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > Create -> POST, Read -> GET, Update -> PUT, Delete -> DELETE

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > ORM stands for Object Relational Mapping. // FIXME 

04. Which two `HTTP` request types include a body?

  > The two HTTP request types that include a body are POST and PUT.

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > In a **synchronous** coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in an **asynchronous** coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.

06. What are the three types of data relationships? Provide an example of each.

  > The three types of data relationships with examples are:
  > * One-To-One (1:1) Ex: User- 1:1 -UID (A user has a single unique identifier and a unique identifier is associated with a single user.)
  > * One-To-Many (1:N) Ex: Stadium- 1:N -Seat (A stadium has many seats. A seat is only related to a single stadium.)
  > * Many-To-Many (N:M) Ex: Student- N:M -Class (A student has many classes and a class has many students.)

07. What is middleware?

  > In the context of Node.js, middleware is a component that sits between incoming requests and outgoing responses in a web apps request-response cycle. It acts as a bridge or intermediary, enabling the processing of requests and responses by adding additional functionality to the application.

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > The **request** pipeline delivers information from the client while the **response** pipeline returns it. Fill in the blanks.

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > The URL pattern for a request query is of the form: **http:// [host] : [port] / [webpage] ? [property] = [value]**
  > An example for this request query would be: **http://localhost:3000/blog?tag=winter**

10. What is a ***virtual property***?

  > Virtuals are additional fields for a given model. Their values can be set manually or automatically with defined functionality. A common virtual property is the full name of a person, composed of user’s first and last name.
