# Class 07 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because JWT is a way for me to securely transfer information on my web applications.

### Intro to JWT
1. What is a JSON Web Token (JWT)?
> JWT is an open standard that defines a compact and self-contained way to securely transmitting information between parties as a JSON object.
2. When should we use JSON Web Tokens?
> We use JSON Web Tokens for scenarios such as: 1. Authorization - allowing user to access routes, services, and resources and 2. Information Exchange - transmitting information between parties.
3. Claims are expected in which structural component of a JWT?
> 

### Are JWTs Secure
1. If I get a JWT and I can decode the payload, how can we call that secure?
> We call that secure because its encrypted and only the receiver that knows the key that validates the content of the payload.
2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
> Sender and receiver must both know some shared secret. In this case, Hash (payload + secret) that gets appended in the signature.
3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
> Concatenated content refers to combining multiple pieces of information into a single message or data stream. When paired with a secret, such as a JSON Web Token (JWT), it ensures that the information is securely packaged and can only be accessed or understood by individuals or systems with the appropriate decryption keys, thus safeguarding sensitive data during transmission and reception.

### JWTs Explained
1. Why use JWT?
> JWT is used to securely transfer information between parties.
2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
> This is useful to a because it can be send via URL, POST request, HTTP Header which means its fast. It allows you to send information about the user and also about logging in to a database by just using a token.
3. What are the three components (the structure) of a JWT signature?
> 1. Header
> 2. Payload
> 3. Signature

### Reflection
1. What are your learning goals after reading and reviewing the class README?
> My learning goal for this be able to apply JWT to my class projects and personal projects.

### Things I want to learn more about.
> Same as Reflection

#### I utilized ChatGPT for some of the questions.
