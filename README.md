# GenerativeAI_AWS_Bedrock_lambda_APIGateway_s3_CloudWatch_Postman

### It's a project to use Generative AI - LLM model using AWS Bedrock
### Tools/ Services used for this Project are 
### 1. AWS Bedrock - Llama 2 Chat 13B (service that offers high-performing foundation models - LLM)
### 2. AWS Lambda (serverless event-driven computing system)
### 3. AWS API Gateway (API service)
### 4. AWS S3 (storage service)
### 5. AWS CloudWatch (monitoring service for AWS rsources and Application)
### 6. Postman (API platform for building and using APIs)

![image](https://github.com/Kamalesh9483/GenerativeAI_AWS_Bedrock_Llama2Chat13B_lambda_APIGateway_s3_CloudWatch_Postman/assets/80197808/ee36db51-0fab-43d1-a731-c39483cb8bdd)

https://github.com/Kamalesh9483/GenerativeAI_AWS_Bedrock_Llama2Chat13B_lambda_APIGateway_s3_CloudWatch_Postman/assets/80197808/823c3bb7-009e-4592-a98b-cbf47db84f0d

Steps
1. Postman Request: A POST request is made in Postman to ask for a blog topic.
2. API Gateway Trigger: The request triggers the AWS API Gateway.
3. Lambda Invocation: The API Gateway triggers an AWS Lambda function.
4. LLM Interaction: The Lambda function sends the blog topic request to AWS Bedrock, using the Llama 2 Chat 13B model.
5. Response Handling: The response from AWS Bedrock is stored in AWS S3.
6. Monitoring: AWS CloudWatch monitors the AWS Lambda function.
