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

Create an Amazon S3 – bucket

<img width="864" height="450" alt="image" src="https://github.com/user-attachments/assets/dd8c62bd-9ef7-427d-a023-0b75885bf419" />

----------------------------------------------------------------------------------------------------------------------------------

Create & update buildspec.yml in Github repo with correct S3 bucket name

<img width="960" height="329" alt="image" src="https://github.com/user-attachments/assets/2d8e5048-9ac1-47e1-8736-ceda530a786d" />

----------------------------------------------------------------------------------------------------------------------------------

Create AWS CodeBuild project and provide proper permission to Codebuild service role

<img width="928" height="508" alt="image" src="https://github.com/user-attachments/assets/b3426543-0bc2-4f71-a6b0-9db316884e70" />

------------------------------------------------------------------------------------------------------------------------------------

<img width="965" height="361" alt="image" src="https://github.com/user-attachments/assets/a3e720ec-d82a-482a-9e0b-b83056277eb6" />

-----------------------------------------------------------------------------------------------------------------------------------

Create AWS CodePipeline: Configure Source stage and Build Stage

<img width="941" height="453" alt="image" src="https://github.com/user-attachments/assets/3b210197-72b9-44a2-bebb-94cb0af51ed3" />

-------------------------------------------------------------------------------------------------------------------------------------

<img width="967" height="465" alt="image" src="https://github.com/user-attachments/assets/5cf3bcb6-3a48-4a88-bba6-4061e907915a" />

-------------------------------------------------------------------------------------------------------------------------------------

Create IAM Role for Deploy stage/service, with proper IAM permissions to it and then configure Deploy stage

<img width="962" height="479" alt="image" src="https://github.com/user-attachments/assets/d2827e61-253b-4010-b301-f10fcbf3f9c1" />

--------------------------------------------------------------------------------------------------------------------------------------

<img width="950" height="507" alt="image" src="https://github.com/user-attachments/assets/b7766f3e-c832-43b6-bb0d-0987ac88d77e" />

--------------------------------------------------------------------------------------------------------------------------------------

The CodePipeline execution gets completed successfully

<img width="951" height="433" alt="image" src="https://github.com/user-attachments/assets/380695c0-18d4-4eea-bf17-c9e0a7b93d76" />

--------------------------------------------------------------------------------------------------------------------------------------

On Cloud Formation section, click on Stacks from left navigation menu

<img width="966" height="345" alt="image" src="https://github.com/user-attachments/assets/43072603-f59b-4ca5-a617-a926c453d1c5" />

--------------------------------------------------------------------------------------------------------------------------------------

Commit a change in Source code at Github repo to trigger CodePipeline automatically

<img width="936" height="441" alt="image" src="https://github.com/user-attachments/assets/f7055327-c4d0-44f4-89cc-2ef685046890" />

-------------------------------------------------------------------------------------------------------------------------------------

Validate the Lambda function deployed under CloudFormation Stack

<img width="920" height="383" alt="image" src="https://github.com/user-attachments/assets/c30e2d28-af44-4216-a7f8-52879a1b4d82" />

------------------------------------------

<img width="944" height="495" alt="image" src="https://github.com/user-attachments/assets/387f9658-a114-4566-82dd-61c7854d29eb" />

------------------------------------------

<img width="943" height="474" alt="image" src="https://github.com/user-attachments/assets/d9994624-fa9c-40bd-bbce-d54fa63e0cb9" />

-----------------------------------------

Validate and Test the ServerlessRestAPI under API gateway

<img width="951" height="433" alt="image" src="https://github.com/user-attachments/assets/a198cdd8-d067-478f-a6cd-dd3ed0371464" />

--------------------------------------------

<img width="964" height="403" alt="image" src="https://github.com/user-attachments/assets/cb932a9f-4803-4bb7-b107-e17189893c38" />

------------------------------------------

<img width="968" height="454" alt="image" src="https://github.com/user-attachments/assets/1d52da1c-001c-4453-81c8-776824b0b9a6" />

-----------------------------------------

<img width="958" height="451" alt="image" src="https://github.com/user-attachments/assets/11e51a36-4719-4901-99d8-8d64aae158a6" />

------------------------------------------------------------------------------------------------------------------------------------

**The above Project implemented a CI/CD pipeline that automates the deployment of this serverless application (AWS Lambda function) by leveraging AWS services such as AWS CodePipeline, CodeBuild, CodeDeploy, AWS CloudFormation and Amazon S3.**

