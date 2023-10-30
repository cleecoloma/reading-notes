# Class 34 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

### Review API Server Build
1. Explain the different between a query string parameter and a path parameter.
> A query string parameter is added to the end of the URL and provides additional information for the request, while a path parameter is part of the URL itself and is used to identify a specific resource.
2. What would our API URL with a path id parameter be given the following information:
> 1. Domain: http://our-site.com
> 2. v3
> 3. model name: stuff
> 4. id: things
>
> The API URL is http://our-site.com/v3/stuff/things
3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
> Imagine our dynamic API interface is like a vending machine. You walk up to it and ask for a specific snack (an API request), and it gives you exactly what you asked for. You don't need to know how the machine works on the inside; you just tell it what you want, and it provides the right snack (data) in response. It's like having a conversation with a vending machine that always gives you the right treat without you needing to understand all the mechanics behind it.

### Review Auth Server Build
1. Describe how you would use middleware to implement basic and bearer auth.
> Middleware can be used to implement basic authentication by checking user credentials before allowing access and bearer authentication by verifying a token provided in the request header for access to protected resources.
2. Describe the handshake necessary to implement OAuth.
> The OAuth handshake involves a user granting permission to a third-party application to access their data. The application redirects the user to the OAuth server, where they log in and authorize the access. The server then provides an access token to the application.
3. Describe how Role Based Access Control works to a non-technical friend.
>Role-Based Access Control works like assigning roles in a play. Each user gets a role (like an actor), and they can only access specific parts of the system based on their role. It ensures that everyone can do their part without interfering with others' roles.

### Things I want to learn more about.

#### I utilized ChatGPT to help with some of the answers