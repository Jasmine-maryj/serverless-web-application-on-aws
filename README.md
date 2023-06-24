# serverless-web-application-on-aws

All the AWS services set up can securely communicate with each other. When a user chooses a button in the web app, it makes a call to an API, which triggers a Lambda function. The lambda function writes to a database and returns a message to a client via API Gateway. IAM manages all of the permissions.

### AWS Amplify
Use of AWS Amplify console to deploy the static resources for web application

### AWS Lambda
Use of AWS Lambda, a compute service that lets you create serverless functions, eliminating the need to manage software and hardware. Instead, applications are broken up into individual functions that can be invoked and scaled individually.

### AWS Dynamo DB
DynamoDB is a key-value database service, so we do not need to create a schema for our data. It has consistent performance at any scale and there are no servers to manage when using it.

### AWS IAM
Use of AWS Identity and Access Management (IAM) service to securely give our services the required permissions to interact with each other. Specifically, allowing a lambda function to write to DynamoDB.

### AWS API Gateway
Use of Amazon API Gateway to create a RESTful API that will allow making calls to Lambda function from a web client. API Gateway will act as a middle layer between the HTML client and the serverless backend.

<p align="center">
  <img src="https://github.com/Jasmine-maryj/serverless-web-application-on-aws/blob/main/architecture/Test%20.png" alt="architectural-view">
</p>
