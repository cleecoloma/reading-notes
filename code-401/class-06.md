# Class 06 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because Authentication is important in securing Personal Identifiable Information. 

### Securing Passwords
1. Explain to a non-technical friend how you would safely hash and store a password.
> To safely hash and store a password, you'd use a one-way hashing algorithm like bcrypt, which takes the password as input, transforms it into a fixed-length string of characters (the hash), and then stores only the hash in your database. You should also add a unique, randomly generated salt to each password before hashing to enhance security.
2. What is Bcrypt?
> Bcrypt is is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.
3. Why might you use something like Bcrypt?
> You might use something like Bcrypt it provides a high level of security and this method of hashing passwords is solid enough for most web applications.

### Basic Auth
1. What is Basic Authentication?
> Basic Authentication is a method for an HTTP user agent to provide a user name and password when making a request.
2. What properties are necessary in the header of a Basic Auth request?
> The properties that are necessary in the header of a Basic Auth request should include "Authorization"
3. How are `username:password` in Basic Auth encoded?
> It is encoded using Base64 encoding.

### OWASP auth cheatsheet
1. Define the authentication process to a non-technical recruiter.
> Authentication is the process of verifying the identity of a user or system trying to access a particular service or resource. It usually involves providing a username and password, which are checked against a database of authorized users to ensure they have the right to access the requested information.
2. How should your error messaging respond (both HTTP and HTML)? Why?
> For HTTP responses, use status codes like 401 (Unauthorized) to indicate authentication failure, and for HTML, provide a user-friendly message like "Invalid username or password." Detailed error messages can expose security vulnerabilities, so it's essential to strike a balance between informative and secure messaging.
3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.
> Okay

### Additional Questions
1. Looking ahead at this module’s course schedule, What do you look forward to learning?
> I look forward to learning more about the inner workings of securing passwords specifically encoding.
2. What are your learning goals after reading and reviewing the class README?
> Learning goal is to learn and understand the upcoming class module to be able to apply it to my future class and personal projects.

### Things I want to learn more about.
> See above.

#### I utilized ChatGPT for some of the questions.
