# serverless-web-application-on-aws
Build a web application on AWS Cloud using AWS Services such as AWS Amplify, AWS IAM, Amazon API Gateway, AWS Lambda, and Amazon DynamoDB.

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
