# Class 06 Summary
## Code 201 - Foundations of Software Development

> These topics relates because JavaScript make our web applications interactive using the Document Object Model.

### JavaScript Object Basics
1. How would you describe an object to a non-technical friend you grew up with?
  > Object is like a dictionary. It is made out of a pair: a key and a value. Let's say you wanted to get a meaning of a word using a dictionary. Key part of an object would be the word in a dictionary while value would be the meaning of the word.
2. What are some advantages to creating object literals?
  > * Ability to reuse code
  > * Use of a shorter syntax
3. How do objects differ from arrays?
  > Object is a pairing system that utilizes keys that corresponds to values while arrays utilizes a index system.
4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
  > 
5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?
  > 
  ```
  const dog = {
    name: 'Spot',
    age: 2,
    color: 'white with black spots',
    humanAge: function (){
      console.log(`${this.name} is ${this.age*7} in human years`);
    }
  }
  ```

### Introduction to the DOM
1. What is the DOM?
  > DOM stand for Document Object Model. It is a tree structure and a way to interact with the elements on a web page usually utilizing JavaScript.
2. Briefly describe the relationship between the DOM and JavaScript.
  > DOM is independent of JavaScript but JavaScript uses the DOM to access the document and its elements.

### Things I want to know more about
  > * I want to know more about how JavaScript would be able to access the DOM and overwrite a text inside it.