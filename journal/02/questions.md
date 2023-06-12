# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > var, let, const

02. What is the definition of a function?

    > A function is a subprogram defined to perform a specific task.

03. What are the `SOLID` principles?

    > The 'SOLID' acronym describes an excellent set of principles to keep in mind while building software. Following these principles will help developers to avoid common architectural mistakes that are extremely difficult to fix down the road. Following these principles help to ensure that your code will be easier to extend and maintain in the future.
      S - Single Responsibility Principle (SRP)
      O - Open-Close Principle (OCP)
      L - Liskov Substitution Principle (LSP)
      I - Interface Segregation Principle (ISP)
      D - Dependency Inversion Principle (DIP)

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > fruit = fruit.filter(function (item) {
        return item !== 'pineapple';
    });

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > you.friends.push(them);
      them.friends.push(you);

06. Give an example of a JavaScript `Conditional`:

    > if (x > 3) {
        console.log("x is greater than 3");
    }

07. What is the main difference between `parameters` and `arguments`?

    > Parameters are the comma-separated set of names used in the function definition. These are the names used within the function to reference the values (arguments) passed in when the function is invoked.
      Arguments refer to the actual values the function reveives for each parameter when the function is invoked. 

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | ANSWER HERE |

09. What is the difference between a `primitive` value and a `reference` value?

    > | ANSWER HERE |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for (x = -100; x <= 100; x++) {
        console.log(x);
    }
