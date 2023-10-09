# Class 18 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because having AWS in my tool belt will help greatly in my job search as most job listing Ive encountered mentions AWS.

### AWS API Gateway Overview
1. What is Amazon API Gateway?
> Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.
2. Why is Amazon API Gateway an important part of the Serverless ecosystem?
>  API Gateway is the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: it enables a truly serverless architecture for web applications. 
3. How does API Gateway integrate with other AWS services?
> When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself.

### AWS API Gateway
1. What are the some benefits of using Amazon API Gateway?
* Efficient API development
* Performance at any scale
* Cost savings at scale
* Easy monitoring
* Flexible security controls
* RESTful API options
2. What two API types might you choose from?
* RESTful APIs
* WEBSOCKET APIs

### AWS DynamoDB Guide
1. What is DynamoDB?
> DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS).
2. Under what circumstances would you recommend DynamoDB over MongoDB?
* Applications with large amounts of data and strict latency requirements.
* Serverless applications using AWS Lambda.
* Data sets with simple, known access patterns.

### AWS DynamoDB
1. Explain to a non-technical friend how DynamoDB works.
> DynamoDB is like a super-fast and highly scalable digital filing cabinet for storing data in the cloud. It organizes information in tables and automatically spreads it across multiple servers, ensuring quick access and reliability for applications without the need for complex setup or maintenance.

### Dynamoose
1. What is Dynamoose?
> Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familiar.
2. What are some key features of Dynamoose?
* Type safety
* High level API
* Easy to use syntax
* DynamoDB Single Table Design Support
* Ability to transform data before saving or retrieving items
* Strict data modeling (validation, required attributes, and more)
* Support for DynamoDB Transactions
* Powerful Conditional/Filtering Support
* Callback & Promise support
* AWS Multi-region support

### Reflection
1. What are your learning goals after reading and reviewing the class README?
> I want to learn more about refactoring my old projects to utilize AWS suite.

### Things I want to learn more about.
> See Reflection above.

#### I utilized ChatGPT to help come up with the ideas.
