# Foundations of Web Development
01. In your own words, why do we use Git?
    > We use git to track versions of code and allow access to a codebase from multiple locations.

02. In the terminal, what is the command `mkdir` used for?
    > This command is used to make a new directory.

03. What is a ***pseudo-class*** and what are some of the most common ones you think you will use?
    > Pseudo-classes are used to define a special state of an element. Some common pseudo-classes are :link, :visited, :hover, :active.

04. What is ***specificity*** and how might you use it to your benefit?
    > When an element is targeted by multiple rules, specificity determines which rules will actually be applied.
    > A benefit would be to apply a general rule to several similar elements, but then a specific rule to one of the elements to override general behavior. 

05. What problems do you think you could run into if you over-utilized the `!important` feature?
    > Using this feature too often can make it difficult to track down specificity issues since it breaks the default rules.
    > When you start overriding default specificity rules, it can be tricky to figure out what rules should apply to certain elements.

06. What are the three components that makeup a `CSS` rule? <br> Example:

    ```css
        h1 {
            color: rgba(255, 210, 33, .75);
        }
    ```

    > selector {
        property: value;
    }

07. How do you think good design influences people when visiting a website, and what sorts of things could you convey through design alone?
    > When a site looks good, it feels good to use and vica versa. A well designed website will attract more traffic and visitors will stay longer. Through design alone, you can create certain emotions for your visitors to help accomplish the site goals. Apple's website is a great example of how design can inspire customers to purchase products.

08. What is the purpose of ***wireframing***?
    > Wireframing helps keep the product aligned with user/stakeholder needs, aids in requirement gathering and feature expectations, while saving developers from spending a lot of build time (company money) during the first iteration. It helps to keep feedback loops short within the agile approach to building software.  

09. Do you think wireframes are worth the time, energy, and effort that they require? Why or Why not?
    > Yes, wireframing will end up saving you time, energy, and effort in the long run. It is critical to the development process to get your product in front of users and stakeholders early and often to make sure that what your building is what the client actually wants. The wireframing process can help developers to clarify requirements as well as give clients a mechanism for communicating what they value.    

10. Define the display `:flex property:`
    > ```css
        .target {
            display: flex;
        }  
      ```
    Flexbox's underlying principle is to make layouts flexible and intuitive. It provides an easier way (than the classic top to bottom block layout) to manage the layout of your site. You can justify (horizontal) content and align (vertical) content much easier than traditional CSS.

11. What `CSS` properties affect the size of a box model?
    > Adjusting properties associated with Margin, Border, and Padding will affect the size of a box model.
