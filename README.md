# PESU Placement Forum

PESU Placement Forum is a web application built using the MERN (MongoDB, Express, React, Node.js) stack, designed to serve as a platform for college students to share and access information about their job placement experiences. The primary purpose of this forum is to facilitate the exchange of insights and knowledge related to interview experiences and coding questions asked during job interviews.

## Key Features

- **Placement Forum**: The core of the application is a forum where college students can share their job placement experiences. This includes details about the company, the interview process, and the questions asked.

- **User Interactions**: Users can engage with posts by leaving comments and upvoting or liking posts, promoting engagement and collaboration within the community.

- **Security**: We have implemented robust security measures, including user authentication and authorization, to protect user data and the integrity of the forum. 
- **Moderation Tools**: To maintain a positive and constructive atmosphere, we have incorporated moderation tools to manage content and user behavior.

- **Authentication**: The project includes Google authentication for user registration and login. Users can authenticate using their Google accounts. In future releases, we can the to implement Google organization-specific authentication as well .

## Getting Started

To set up and run this project on your local machine, follow these steps:

1. **Clone the Repository**: Start by cloning this repository to your local machine using Git.

   ```bash
   git clone https://github.com/akhileshharkude/MiniProjFinal.git
2. Install Dependencies: Navigate to the project directory and install both client and server dependencies.
    ```bash
    cd MiniProjFinal
    cd client
    npm install
    cd ..
    npm install

3. Set Up MongoDB: Install and configure MongoDB. Create a database for the application to store user data and posts.

4. Update MongoDB Connection String: Open server/index.js and update the MongoDB connection string on line 19 with your database connection details.

5. Start the Development Server: Run the following command to start both the server and the client.
   ```bash
   npm start

  The application should now be accessible at http://localhost:3000.

