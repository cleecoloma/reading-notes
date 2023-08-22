# Class 08 Summary
## Code 301 - Intermediate Software Development

> These topics relates because API is an integral part of backend web development and learning how to properly utilize it will impact how our clientele.

### API Design Best Practices
1. What does REST stand for?
> REST stands for Representational State Transfer
2. REST APIs are designed around a ____.
> resources.
3. What is an identifier of a resource? Give an example.
> Identifier of a resource is a unique word that identifies a specific resource. This identifier is often used a part of the resource's URI.
> An example would be API key we used for the location IQ API.
4. What are the most common HTTP verbs?
> POST, GET, POST, PATCH, DELETE
5. What should the URIs be based on?
> URIs should be based on resources that the API provides.
6. Give an example of a good URI.
> * API Base URL: `https://api.pokedex.com`
> * `https://api.pokedex.com/types` provides different types of pokemon.
> * `https://api.pokedex.com/abilities` provides different list of pokemon abilities.
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
> 'Chatty' web API means that you need multiple requests to retrieve a piece of information.
> There are pros and cons. One advantage about 'chatty web API is that it allows users to retrieve only a specific information which can reduce data transfers. One disadvantage is that it can affect user experience where nowadays everyone wants everything instantly.
8. What status code does a successful `GET` request return?
> 200
9. What status code does an unsuccessful `GET` request return?
> 4XX or 5XX range status codes
10. What status code does a successful `POST` request return?
> 200 OK or 201 Created
11. What status code does a successful `DELETE` request return?
> 200 OK or 204 No Content

### Things I want to learn more about.
> I want to learn about creating my own API.


###### I also utilized ChatGPT with some of the questions.