# Class 18 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because having AWS in my tool belt will help greatly in my job search as most job listing Ive encountered mentions AWS.

### AWS SQS vs SNS
1. What is the difference betweeen SQS and SNS?
> SQS (Simple Queue Service) is a message queue service that allows decoupling of components in an application, while SNS (Simple Notification Service) is a publish-subscribe messaging service that enables message distribution to multiple subscribers. The key difference is that SQS stores messages in a queue for one-time processing by a single consumer, whereas SNS delivers messages to multiple subscribers in real-time.
2. What are some use cases for both SNS and SQS?
> Use cases for SNS include sending notifications to multiple subscribers (e.g., email, SMS, or Lambda functions) in real-time when events occur, like system alerts or updates. SQS is suitable for managing workloads with asynchronous processing, such as order processing, image resizing, or background tasks.

### AWS SNS and SQS
1. Describe how to use SQS and SNS in a “fanout” pattern.
> To implement a "fanout" pattern using SQS and SNS, you can configure SNS to publish messages to multiple SQS queues. Subscribers (consumers) can then poll these SQS queues for messages, allowing parallel processing of the same message by multiple consumers.
2. Explain how “push notifications” work, using SNS.
> In a "push notifications" scenario using SNS, you create a topic and subscribe endpoints (e.g., mobile devices or email addresses) to it. When you publish a message to the SNS topic, it automatically delivers the message to all subscribed endpoints, allowing you to send notifications to multiple recipients simultaneously.

### SQS and SNS Basics
1. How might a large scale, distributed application make use of a Queue system like SQS?
> In a large-scale, distributed application, SQS can be used to decouple components and handle increased workloads. For example, if you have a web application with heavy traffic, you can use SQS to queue requests for processing by backend services. This ensures that even during traffic spikes, requests are managed efficiently and no data is lost, promoting scalability and fault tolerance.

### Reflection
1. What are your learning goals after reading and reviewing the class README?
> I want to learn more about refactoring my old projects to utilize AWS suite.

### Things I want to learn more about.
> See Reflection above.

#### I utilized ChatGPT to answers the questions.