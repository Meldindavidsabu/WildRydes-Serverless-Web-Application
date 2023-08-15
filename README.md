
A serverless web application using AWS Lambda, Amazon API Gateway, AWS Amplify, Amazon DynamoDB, and Amazon Cognito.
# Wild Rydes Unicorn Rides Web Application

Welcome to the Wild Rydes Unicorn Rides Web Application tutorial! In this project, you'll create a captivating serverless web application that lets users request magical unicorn rides from the Wild Rydes fleet. The application boasts an enticing HTML-based user interface, allowing users to pinpoint their desired pickup locations. Behind the scenes, a robust RESTful web service handles ride requests, dispatching nearby unicorns to fulfill users' dreams. Additionally, the application offers user registration and login functionalities to enhance the overall experience.

<img width="591" alt="wild rydes" src="https://github.com/Meldindavidsabu/WildRydes-Serverless-Web-Application/assets/80899101/0c6605a4-cc52-470c-812f-7f3decbbf7f6">

## Prerequisites

Before diving into this enchanting project, make sure you have the following:

- An AWS account to leverage the power of cloud services.
- An ArcGIS account for incorporating maps into your app.
- A text editor to craft your code.
- A web browser for testing your creation.

## Application Architecture

Application's architecture combines several AWS services to deliver a seamless experience:

### Static Web Hosting with AWS Amplify

AWS Amplify comes to the rescue by hosting static web resources such as HTML, CSS, JavaScript, and images. These resources are skillfully loaded in users' browsers, ensuring a visually stunning and interactive interface.

### User Management via Amazon Cognito

Amazon Cognito steps in to provide comprehensive user management and authentication functions, reinforcing the security of our backend API.

### Serverless Backend Powered by Amazon DynamoDB

The heart of our application lies in Amazon DynamoDB, which serves as a persistent storage layer. The backend API's Lambda function skillfully stores and retrieves data here, making the magic happen behind the scenes.

### RESTful API with Lambda and API Gateway

Our application's frontend interacts with the backend through a public RESTful API built using AWS Lambda and API Gateway. JavaScript code executed in users' browsers seamlessly sends and receives data, creating a dynamic and captivating user experience.

## Getting Started

Follow these steps to bring your Wild Rydes Unicorn Rides Web Application to life:

1. **Clone the Repository:** Begin by cloning the repository to your local machine.
<img width="956" alt="resources on codecommit" src="https://github.com/Meldindavidsabu/WildRydes-Serverless-Web-Application/assets/80899101/d07cf5c3-43c4-46e0-a5ed-ee6aa24cb81a">

<img width="390" alt="git (original)" src="https://github.com/Meldindavidsabu/WildRydes-Serverless-Web-Application/assets/80899101/ae5edc4a-73f1-46cc-b1e8-9cd1cd555c85">

3. **Setting up AWS Services:**
   - **Amplify Console:** Set up Amplify Console to host your static web resources. Configure deployment settings to ensure continuous deployment.
   - **Amazon Cognito:** Create a user pool to manage user registration and authentication.
   - **Amazon DynamoDB:** Establish a DynamoDB table to store ride request data.

4. **Integrate ArcGIS Mapping:**
   - Leverage your ArcGIS account to incorporate captivating maps into your application. 

5. **Backend Setup:**
   - Implement the Lambda function that handles ride requests and interacts with DynamoDB.
   - Create an API Gateway to expose the Lambda function as a RESTful API.

6. **Frontend Development:**
   - Craft a visually appealing HTML-based user interface that allows users to specify pickup locations.
   - Write JavaScript code to interact with the backend API, enabling users to request unicorn rides.

7. **User Registration and Login:**
   - Integrate Amazon Cognito into your application to manage user authentication and provide registration and login functionalities.

8. **Test and Deploy:**
   - Thoroughly test your application, ensuring that ride requests, user registration, and login functionalities work flawlessly.
   - Deploy your application using Amplify Console, making it accessible to users around the world.

## Embrace the Magic

Congratulations! You've successfully created a captivating serverless web application that brings the wonder of unicorn rides to life. By harnessing the power of AWS services and innovative frontend development, you've crafted an experience that users will cherish.

For detailed documentation, troubleshooting tips, and updates, visit https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/ .
