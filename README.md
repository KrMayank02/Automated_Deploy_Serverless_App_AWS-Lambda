# Automated Deployment of Serverless Application using AWS Lambda and AWS CodePipeline

**Objective:** To deploy a Lambda function using AWS CodePipeline to automate the retrieval of current temperature data for New York city via an external API.

**Real-time Scenario:** Weather Metrics, a dynamic weather analytics company, specializes in providing real-time weather data and forecasts to various industries, including agriculture, transportation, and event planning.
The company is advancing its analytics capabilities by implementing a Lambda function that fetches current temperature data for major cities. This enhancement is part of their initiative to provide more accurate and timely weather updates to their clients using AWS technologies.
As a cloud solutions architect at Weather Metrics, you are responsible for orchestrating the CI/CD pipeline that automates the deployment of this serverless application. Your task involves ensuring that the deployment process is seamless, scalable, and maintains high availability, leveraging AWS services such as AWS CodePipeline, AWS CodeBuild, and Amazon S3.


## Major Tools, Service, Environment Used in This Project:

- AWS Lambda
- AWS CodePipeline
- AWS CodeBuild
- AWS CodeDeploy
- AWS CloudFormation
- S3
- API Gateway


## High Level Project Diagram:

<img width="946" height="597" alt="image" src="https://github.com/user-attachments/assets/104461c7-7b99-4647-96c1-43e1e32eeb0d" />

------------------------------------------------------------------------------------------------------------------------------------

## High Level Tasks/Steps:

-	Fork the Lambda function project Github repository.
-	Create an Amazon S3 – bucket.
-	Create & update buildspec.yml in Github repo with correct S3 bucket name.
-	Create AWS CodeBuild project and provide proper IAM permission to Codebuild service role.
-	Create AWS CodePipeline: Configure Source stage and Build Stage.
-	Create IAM Role for Deploy stage/service, with proper IAM permissions and then configure Deploy stage.
-	Commit a change in Source code at Github repo to trigger CodePipeline automatically.
-	Validate the Lambda function deployed under CloudFormation Stack.
-	Validate and Test the ServerlessRestAPI under API gateway.

## Output Results Screenshots:

