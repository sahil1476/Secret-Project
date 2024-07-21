# Secret Sharing Project

This project is a web application built using Node.js, Express, and EJS. It allows users to register, log in, and submit anonymous secrets. The application uses Google OAuth for authentication and implements password encryption for added security.

## Features

- User registration with encrypted passwords
- Google OAuth for secure authentication
- Login and logout functionality
- Submit anonymous secrets
- View submitted secrets (optional or for admin users)

## Technologies Used

- Node.js
- Express.js
- EJS (Embedded JavaScript templates)
- MongoDB (or PostgreSQL)
- Passport.js (for authentication)
- BCrypt (for password encryption)

## Getting Started

Follow these instructions to set up the project on your local machine for development and testing purposes.

### Prerequisites

- Node.js and npm installed
- MongoDB or PostgreSQL database setup
- Google Developer account for OAuth setup

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/sahil1476/secret-sharing-project.git
    cd secret-sharing-project
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Set up environment variables:

    Create a `.env` file in the root directory and add the following variables:

    ```plaintext
    PORT=3000
    DATABASE_URL=your_database_url
    GOOGLE_CLIENT_ID=your_google_client_id
    GOOGLE_CLIENT_SECRET=your_google_client_secret
    SESSION_SECRET=your_session_secret
    ```

4. Start the application:

    ```bash
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000`.

## Usage

- Register a new account or log in using Google OAuth.
- Once logged in, you can submit your secrets anonymously.
- View the submitted secrets on the secrets page (customize based on your requirements).

## Project Structure

![image](https://github.com/user-attachments/assets/f88ee11e-0407-4a26-8e67-579c10b6f921)
