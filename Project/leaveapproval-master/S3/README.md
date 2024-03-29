# leaveapproval
**Services**:
The mechanism you are referring to is the flow of data between various AWS services, such as:**
API Gateway
AWS DynamoDB
AWS SES
AWS S3
AWS Lambda**
**
Mechanism:
Here is a brief explanation of how this mechanism works:**

1. An HTML form is hosted on a web page and served to the user through a web server. The user fills out the form with their details and submits it.

2. The form data is sent to API Gateway, which is a fully managed service that allows developers to create, deploy, and manage APIs at any scale. API Gateway acts as a front door for the backend services and APIs that power the application, and it is responsible for securely routing the request to the appropriate backend service or function.

3. The request is then forwarded to a Lambda function, which is a serverless compute service that runs code in response to events and automatically manages the underlying compute resources. The Lambda function receives the form data and performs the necessary processing, such as storing the data in DynamoDB and sending an email notification.

4. The Lambda function interacts with DynamoDB, which is a fast and flexible NoSQL database service that provides consistent, single-digit millisecond latency at any scale. DynamoDB is used to store the form data and retrieve it later when needed.

5. The Lambda function also interacts with SNS, which is a highly available, durable, secure, fully managed pub/sub messaging service that enables decoupling and scaling microservices, distributed systems, and serverless applications. SNS is used to send a message to a topic, which can then be delivered to multiple recipients, such as email addresses, mobile devices, and other endpoints.

6. Finally, the Lambda function interacts with SES, which is a highly scalable, cost-effective, and flexible email-sending service that enables businesses to send transactional emails, marketing messages, and other types of high-quality content to their customers. SES is used to send an email notification to the user, confirming that their form submission has been received and processed.
Overall, this mechanism leverages the power of multiple AWS services to provide a scalable, reliable, and cost-effective solution for processing HTML form submissions and storing them in DynamoDB while also sending email notifications to the user.

![image](https://github.com/MuluguVeeraVamshi/leaveapproval/assets/93989243/89069c34-c2e7-4a2b-b7e3-24e1743ecc8f)

![image](https://github.com/MuluguVeeraVamshi/leaveapproval/assets/93989243/197cec36-c9a0-451d-ab75-d6ffc6cdc4f7)

![image](https://github.com/MuluguVeeraVamshi/leaveapproval/assets/93989243/c9e0cf9b-2f74-4f12-982c-9177678eb77c)

![image](https://github.com/MuluguVeeraVamshi/leaveapproval/assets/93989243/933ad79b-5151-4087-9c28-7c4ca0b11187)

Verification If the email is not identified in the SES: new member, then
![image](https://github.com/MuluguVeeraVamshi/leaveapproval/assets/93989243/7f8c2f22-d891-4fb7-be5a-386434aa70f6)

![image](https://github.com/MuluguVeeraVamshi/leaveapproval/assets/93989243/48851fb4-6d38-418a-846a-bbfa9d0691c4)

![image](https://github.com/MuluguVeeraVamshi/leaveapproval/assets/93989243/6780508b-3553-4149-8eb1-bb064bc6a40f)

![image](https://github.com/MuluguVeeraVamshi/leaveapproval/assets/93989243/9c4f0aec-8e61-458b-86d8-08733e26edf8)
