# 🤐🤐Secret Sharing Project🤐🤐

This project is a web application built using Node.js, Express, and EJS. It allows users to register, log in, and submit anonymous secrets. The application uses Google OAuth for authentication and implements password encryption for added security.

## Demo Video


Click the button below to watch the demo video:

[![Watch the video](<svg fill="#000000" height="200px" width="200px" version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="-10.2 -10.2 80.40 80.40" xml:space="preserve" stroke="#000000" stroke-width="3.66"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <g> <path d="M45.563,29.174l-22-15c-0.307-0.208-0.703-0.231-1.031-0.058C22.205,14.289,22,14.629,22,15v30 c0,0.371,0.205,0.711,0.533,0.884C22.679,45.962,22.84,46,23,46c0.197,0,0.394-0.059,0.563-0.174l22-15 C45.836,30.64,46,30.331,46,30S45.836,29.36,45.563,29.174z M24,43.107V16.893L43.225,30L24,43.107z"></path> <path d="M30,0C13.458,0,0,13.458,0,30s13.458,30,30,30s30-13.458,30-30S46.542,0,30,0z M30,58C14.561,58,2,45.439,2,30 S14.561,2,30,2s28,12.561,28,28S45.439,58,30,58z"></path> </g> </g></svg>)](https://www.canva.com/design/DAGLeAARK4E/-BpYRE88vUjXLY1Qa8ygHQ/view)


## Features

- User registration with encrypted passwords
- Google OAuth for secure authentication
- Login and logout functionality
- Submit anonymous secrets
- View submitted secrets (optional or for admin users)

## Technologies Used 💻💻💻

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
    git clone https://github.com/sahil1476/Secret-Project.git
    cd Secret-Project
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Set up environment variables:

    Create a `.env` file in the root directory and add the following variables:

    ```plaintext
    GOOGLE_CLIENT_ID="demo-id-1223456789-678876543.apps.googleusercontent.com"
    GOOGLE_CLIENT_SECRET="aasdfghjklkjhgfdfghjkjhgfdfghjkjhg"
    SESSION_SECRET="TOPSECRETWORD"
    PG_USER="postgres"
    PG_HOST="localhost"
    PG_DATABASE="db_name"
    PG_PASSWORD="abcdef"
    PG_PORT="5432"
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


## Acknowledgments

- [Google Developers](https://developers.google.com/) for OAuth
- [Passport.js](http://www.passportjs.org/) for authentication
- [BCrypt](https://www.npmjs.com/package/bcrypt) for password hashing
- [Express](https://expressjs.com/) for the web framework
- [EJS](https://ejs.co/) for templating

