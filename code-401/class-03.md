# Class 03 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because they have specific roles on web application developments.

### Review: ES6 Classes
1. Classes are a template for creating ____.
> Classes are a temple for creating **objects**.
2. Can a class declaration be hoisted?
> Class declaration cannot be hoisted.
3. How would you describe a constructor and contextual “this” to a non-technical friend?
> A constructor is like a blueprint for creating something, specifying how it should be built and what initial characteristics it should have, similar to a recipe for baking a cake. "this" is a word we use to point to the specific thing we are currently working on, making it easier to add the right ingredients to the right cake, or make changes to the right object in programming.

### Using Express Routing
1. Within Express, what does routing refer to?
> Routing refers to how an application’s endpoints (URIs) respond to client requests.
2. What is the difference between a route path and a route method?
> A route method is derived from one of the HTTP methods, and is attached to an instance of the express class.
> Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.
3. When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?
> It is appropriate to add `next` as a parameter to a route handler when you want to pass control to the next middleware or route handler in the chain.
> If `next` has been passed to your middleware as a parameter, you must call it within your middleware to ensure that Express proceeds to the next middleware or route handler. If not, your application may hang or not continue processing subsequent middleware in the chain.

### Express Routing
1. What is an Express Router?
> Express Router is a mini express application without all the bells and whistles of an express application, just the routing stuff.
2. By what mean do we initialize `express.Router()` in an express server?
```javascript
const express = require('express');
const router = express.Router();
```
3. What do we use route middleware for?
> Route middleware is used to perform actions or operations that should be executed before or after handling a specific route.

### Reflection
1. What are your learning goals after reading and reviewing the class `README`?
> Some learning goals I have after reading and reviewing the class `README` are learn more about SQL and try to implement them in personal projects.

### Things I want to learn more about.
> I want to learn more about how to use `next` when using express.

#### I utilized ChatGPT for some of the questions.
