# Thinkora

Thinkora is an ED Tech (Education Technology) web application developed using the MERN stack.

## Features

- **User Authentication**: Thinkora provides secure user registration and authentication using JWT (JSON Web Tokens). Users can sign up, log in, and manage their accounts.
- **Course Management**: Instructors can create, update, and delete courses. Each course can have multiple sections and lessons.
- **Progress Tracking**: Thinkora allows students to track their progress in enrolled courses. They can view completed lessons, scores on quizzes and assignments, and overall course completion status.
- **Payment Integration**: Thinkora integrates with Razorpay for payment processing. Users can make secure payments for course enrollment and other services.
- **Cloud-Based Media Management**: The application uses Cloudinary for storing and managing media content, such as course videos and images.

## Technologies Used

- MongoDB
- Express.js
- React.js
- Node.js
- Cloudinary
- Razorpay

## Installation

To run the application locally, follow these steps:

1.  Clone the repository:

    git clone https://github.com/your-username/thinkora.git

2.  Install the dependencies for the server:

    cd server
    npm install

3.  Install the dependencies for the client:

    cd ../client
    npm install

4.  Create a `.env` file in the `server` directory and add the following environment variables:

    PORT=4000
    MONGODB_URL=your-mongodb-connection-string
    JWT_SECRET=your-jwt-secret
    CLOUDINARY_API_KEY=your-cloudinary-api-key
    CLOUDINARY_API_SECRET=your-cloudinary-api-secret
    RAZORPAY_KEY_ID=your-razorpay-key-id
    RAZORPAY_SECRET=your-razorpay-secret

5.  Start the server:

    npm start

6.  Start the client:

    npm start

## Usage

Once the application is running, you can open it in your browser at `http://localhost:3000`. You can then sign up as a new user or log in with an existing account to access the features of the application.

## Note

This project is intended as a learning tool and can be used as a sample project for educational or personal projects.


***
## Screenshots
![Screenshot 2023-07-25 210844](https://github.com/himanshu8443/Thinkora-master/assets/99420590/0cba8d5b-6a47-4721-ac9f-4279107c257e)
![Screenshot 2023-07-25 211309](https://github.com/himanshu8443/Thinkora-master/assets/99420590/62c33b56-0bd5-4330-b1db-d41b80d9f69f)
<details>
  <summary>More screenshots</summary>
  
![Screenshot 2023-07-25 211451](https://github.com/himanshu8443/Thinkora-master/assets/99420590/63f7163d-a74a-4e78-bc78-6b96b06073f9)
![image](https://github.com/himanshu8443/Thinkora-master/assets/99420590/59d1d8c2-2824-45bb-a2f7-6f5dc234895c)
</details>

***

## Important
* Backend is  in the server folder.
* Before uploading courses and anything create the categories e.g. web dev, Python, etc. (without categories courses cannot be added). To create categories create an Admin account and go to dashboard then admin panel.
* To create an Admin account first sign up with a student or instructor account then go to your Database under the users model and change that 'accountType' to 'Admin'.
