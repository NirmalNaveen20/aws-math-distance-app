# AWS Math Web Application Project

## 📌 What is this project?

This project is designed to help AWS beginners understand how to connect and use multiple AWS services to build a real-world web application. This project will build a simple math web app from scratch, leveraging **five AWS services**:

- AWS Amplify
- AWS Lambda
- Amazon API Gateway
- Amazon DynamoDB
- AWS Identity & Access Management (IAM)

By the end of this project, you will have a fully functional application hosted on AWS that performs math calculations using a backend Lambda function.

---

This project teaches you how to **apply** AWS knowledge to create a practical application that integrates front-end hosting, APIs, serverless compute, NoSQL databases, and IAM security.

---

## What do you need to know before starting?

### Recommended Skills:
- Basic understanding of AWS.
- Completion of **AWS Certified Cloud Practitioner** or any beginner AWS course is helpful.

---

## Tools and Services Used

- **AWS Amplify**: Hosts the front-end HTML page.
- **AWS Lambda (Python)**: Executes backend logic for the application.
- **Amazon API Gateway**: Connects the front-end to the Lambda function via HTTP requests.
- **Amazon DynamoDB**: Stores any necessary data.
- **AWS IAM**: Controls access permissions between services (execution role for Lambda).

---

## Project Files

The project includes the following files:

- `index-ORIGINAL.html` - Original front-end HTML file (rename to `index.html` before use).
- `index-FINAL.html` - Final version of the front-end HTML.
- `Execution Role Policy JSON.txt` - JSON file for IAM execution policy for Lambda.
- `TwoPointOhFunction - Lambda-ORIGINAL.txt` - Starter Lambda function (Python).
- `TwoPointOhFunction - Lambda-FINAL.txt` - Final version of the Lambda function.
- `Latitude and Longitude Test Points.txt` - Example data points for testing the application.

---

## How to Run the Project

1. **Upload the HTML file to AWS Amplify** to host the front-end.
2. **Create a Lambda function** in AWS using the provided Python script.
3. **Set up an API Gateway** to expose the Lambda function to the web.
4. **Create a DynamoDB table** if required by the Lambda logic.
5. **Attach the provided IAM policy** to the Lambda execution role.
6. **Test the application** using the provided test points.

---

## Final Output

A deployed web application on AWS that allows users to input values and receive math-related results via serverless backend logic. All AWS services work together to provide a seamless, fully integrated cloud-hosted solution.

---

## Demo Screenshots

_(Add screenshots here once the app is deployed)_

---

## 🏷️ Tags

`#AWS` `#Serverless` `#Lambda` `#Amplify` `#DynamoDB` `#API-Gateway` `#IAM` `#CloudProject` `#Portfolio`