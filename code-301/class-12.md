# Class 12 Summary
## Code 301 - Intermediate Software Development

> These topics relates because status codes are a way for us to determine why our request did or didn't work.

### Status Codes Based On REST Methods
1. In your own words, describe what each group of status code represents:
> 100’s = Informational
> 200’s = Success
> 300’s = Redirection
> 400’s = Client Error
> 500’s = Server Error
2. What is a status code 202?
> Request was accepted but server needs tme processing and will finish at some point.
3. What is a status code 308?
> Permanent redirect - tells client to utilize another URL to access resource.
4. What code would you use if an update didn’t return data to a client?
> Status Code 204 No Content
5. What code would you use if a resource used to exist but no longer does?
> Status Code 410 Gone
6. What is the ‘Forbidden’ status code?
> The client has authorized or doesn't need to authorize itself, but still has no permissions to access the resource.

### Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes
1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
> We do this to protect store sensitive information.
2. What is middleware?
> Middleware refers to a software component or layer that sits between the incoming HTTP requests and the actual application logic
3. What does `app.use(express.json())` do?
> `app.use(express.json())` let the server accept JSON as a body instead of post or get element.
4. What does the `/:id` mean in a route?
> `/:id` is a parameter.
5. What is the difference between `PUT` and `PATCH`?
> `PUT` is used to update or create a resource while `PATCH` is used to apply partial modifications to a resource.
6. How do you make a default value in a schema?
> By assigning a "default" key.
7. What does a `500` error status code mean?
> Status `500` means Internal Server Error.
8. What is the difference between a status `200` and a status `201`?
> Status `200` tells the client everything went good while status `201` tells the client that a resource was created on the backend-side.

### Things I want to learn more about.
> None


###### I also utilized ChatGPT with some of the questions.