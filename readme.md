# 🤐🤐Secret Sharing Project🤐🤐

This project is a web application built using Node.js, Express, and EJS. It allows users to register, log in, and submit anonymous secrets. The application uses Google OAuth for authentication and implements password encryption for added security.

Watch the demo video below:

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAGLeAARK4E&#x2F;-BpYRE88vUjXLY1Qa8ygHQ&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAGLeAARK4E&#x2F;-BpYRE88vUjXLY1Qa8ygHQ&#x2F;view?utm_content=DAGLeAARK4E&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Simple Presentation in Pink Lilac Pastel Blobs Basic Style</a> by Sahil 120120716
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

