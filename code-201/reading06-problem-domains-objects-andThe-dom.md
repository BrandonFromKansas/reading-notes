# Problem Domain, Objects and the DOM (Document Object MOdel)

### [JavaScript: Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

##### 1. How would you describe an object to a non-technical friend you grew up with?
- I would compare it to the Russian nesting dolls. There is one container that houses smaller ones beneath it. Each one has its own unique look. Their placement is crucial to making all the dolls work together. You cannot place a larger doll inside of a smaller one because that would break the rules and break the object.

##### 2. What are some advantages to creating object literals?
- It is far more efficient to send one piece of data altogether as opposed to sending one piece of code individually. 
- Object literal: creates an object using a concise and straightforward syntax. It allows developers to define an object and its properties in a single exprssion, without the need for a separate constructor function.
![Definition of Object Literal](./code-201/assets/ChatCPT.ObjectLiteral.png)
*Credit: [ChatGPT](https://chat.openai.com/share/bb4a1d3b-3f30-4716-953f-4dd1ce775ea5)

##### 3. How do objects differ from arrays?
- Object literals and Arrays are both *types* of objects but they do server different purposes.
- Object literals are great for when a developer needs to transfer a series of structured, related data items of some manner (such as sending a request to the server to be put into a database). Sending just a single *object* is more efficient that sending several items individually.
- Objects are easier to work with ass opposed to Arrays when a developer needs/wants to identify individual items by name.

##### 4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
- While **dot notation** is generally preferred over **bracket notation** (because dot notation is more succinct and easier to read), there are a few instances when **bracket notation** needs to be used.
- Example: if an object prperty name is stored in a variable, then the developer cannot use **dot notation** to access the value. They must access the value using **bracket notation**.

##### 5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?
![Evaluate this block of code for reading06](./code-201/assets/EvaluateThisBlockOfCodeReading06.png)

- The use of `this.` allows `humanAge` to refer back to the *name* and *age* specific properties of the `const dog` object literal.
- Using `this` allows a developer to dynamically target properties inside of the previously declared object literal.


### [Introduction to the DOM (Document Object Model)](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

##### 1. What is the DOM?
- Document Object Model: is the data representation of the objects that comprise the structure and content of a document on the web. 
- It is considered a **programming interface** for web documents.
- It represents the page so that programs can change the document structure, style and content.
- The DOM represents the document as nodes and objects so that other programming languages can interact with the page.

##### 2. Briefly describe the relationship between the DOM and JavaScript.
- The DOM (Document Object Model) is a programming interface for web documents and it represents the structure of HTML documents (it provides a blueprint).
- JavaScript can then manipulate the DOM by accessing groups of elements, or, even very specific elements. JavaScript can modify attributes, add or remove elements, and it responds to events which may be triggered by user interaction. JavaScript allows developers to create a dynamic experience for the users. Combined together, they serve as very powerful tools for "creating powerful and responsive web applications." * Credit: [ChatGPT](https://chat.openai.com/share/afd049fa-1414-4dd9-9d40-cc91b10223ec)