# AWS Company Email Scheduler Project

## Overview
Creating a simple, scalable and serverless  email  schedule service with multiple different AWS Services.

## AWS Services Used

- **Amazon Simple Email Services (SES):**
- **AWS Lambda:**
- **Amazon Simple Storage Service (S3):**
- **Amazon Event Bridge:**
- **AWS IAM:**

## 1.) Setting up the backbone of this project with an S3 bucket
The first step was to set up an S3 bucket to store an HTML file containing the email template and a .csv file to store the recipients targeted by the email. While there are more intricate methods available to tailor to specific company needs, this project focuses on simplicity.
<img src="https://i.imgur.com/caVi6A9.png" height="80%" width="80%" alt="Code commit permissions"/>
<br />
<br />

## 2.) Configuring Simple Email Service (SES)
Next, SES settings were configured to establish an email account capable of sending out emails according to company requirements.

## 3.) Creating a Lambda function for serverless email sending
A Lambda function was created specifically to send emails to targeted recipients when invoked.

## 4.) Using EventBridge to complete the project
Finally, an EventBridge scheduler was set up to trigger the Lambda function on a time-based schedule. For this project, a one-week interval was chosen, but the timing can be adjusted according to the company's requirements.
<img src="https://i.imgur.com/DjjNtzZ.png" height="80%" width="80%" alt="Code commit permissions"/>
<br />
<br />

## 5.) Credit to Tiny Tech Tutorials for their recommendation! Check out their YouTube channel here.
Thanks to Tiny for recommending eraser.io, a website where you can set up architecture as code for your projects. This resource greatly helped in understanding the project architecture.
<img src="https://i.imgur.com/KeBnKTq.png" height="80%" width="80%" alt="Code commit permissions"/>
<br />
<br />


