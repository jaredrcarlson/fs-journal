# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > Abstraction, Encapsulation, Inheritance, and Polymorphism

02. How does `export` differ from `export default`?
  
  > `Export default` is used to export a single value as the default export, while `export` with named exports is used to export multiple values as named exports.

03. What is Encapsulation?
  
  > Encapsulation brings data and the methods which operate on them together in a single unit. Encapsulation helps to control access to the unit.

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > A Proxy object allows us to set `traps` when an object is accessed. We can change the default behaviors of `get` and `set` methods to add custom operations. Some benefits would be logging events for when an object's properties are read (get) or written (set). We can also use a Proxy object to prevent access to certain properties that we want to keep private by throwing an error within our custom get method instead of returning a value. Using a Proxy object to write a custom set method also allows us to validate data type values prior to assigning them to our object's properties.

05. What the difference between a `class` and an instance of a `class`?
  
  > A class is a blueprint for creating an object while an instance is an actual object that has been created from the blueprint.

06. What is a computed Property?
  
  > ES6 allows you to use an expression in brackets []. It’ll then use the result of the expression as the property name of an object. (This is super interesting to me)

07. What is the purpose of the `MVC` pattern?
  
  > The purpose of the MVC pattern is to make code easier to manage and develop by breaking up the frontend and backend pieces. Changes on either end should not cause issues on the other end if they are properly decoupled.

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > The Controller responds to user input and performs interactions on the data model objects and updates the View with changes in the Model. (The Brains) 

09. What is the job of the `Service` in `MVC`?
  
  > The View handles data visualization. It is responsible for data presentation.
    Services are implemented to isolate business logic from the rest of the application.

10. What is the job of the `Model` in `MVC`?
  
  > The Model recieves user input from the Controller and is responsible for managing the data of the application. The model handles data representation.
