# aws-lambda-basics
AWS Lambda, provided by Amazon Web Services, is a serverless platform that helps code execution without the need to manage underlying servers. 

In this repo we will start  by creating a Lambda function with Python, incorporating the requests library to enable API interactions. Then, we will package and deploy this function with its dependencies. Next, we will optimize by creating a Lambda layer with the requests library, allowing for more efficient code editing and package management.

 we'll also delve into sentiment analysis by adding the textblob library to a Lambda layer and applying this to analyze text data. Finally, we will  learn to share this textblob layer across multiple Lambda functions, including the analysis of the text from an image stored in an S3 bucket.

This repo is aimed at gaining practical experience in integrating and managing Lambda layers within AWS Lambda functions.

The following is the high-level architecture diagram

image.png

1.Introduction
Getting Started

2.Lambda with Deployment Package
Create a Lambda Function and Fetch API Details
Create a Deployment Package

3.Lambda Function with Layers
Reduce the Package Size and Enable Code Edit
Focus on Core Logic with Lambda Layers
Share Dependencies across Lambda Functions

4.Conclusion
Clean Up
