# Authentication-Secrets

This project is a web application built with Node.js, Express, and MongoDB, allowing users to authenticate, share secrets, and sign in via Google OAuth 2.0.

## Features
* User registration and login with username/password or Google OAuth.
* Secure password storage using Passport.js and bcrypt.
* Ability for authenticated users to submit secrets anonymously.
* Display of submitted secrets from authenticated users.
* Logout functionality to end user sessions.
## Setup
1. Clone the repository:
Copy code
`git clone https://github.com/MausamGaikwad/Authentication-Secrets-Final.git`
2. Install dependencies:
Copy code
`npm install`
3. Set up a MongoDB database and provide the connection URI in the `.env` file.
4. Obtain Google OAuth credentials and update the `.env` file with the client ID and secret.
5. Start the server:
Copy code
`npm start`
6. Access the application in your web browser at `http://localhost:3000`.
## Usage
* Register a new account or sign in using your Google account.
* Share your secrets anonymously on the platform.
* View secrets submitted by other users.
## Technologies Used
* Node.js
* Express
* MongoDB
* Passport.js
* OAuth 2.0 (Google)
* EJS (Embedded JavaScript)
* Bootstrap
## Contributing
Contributions are welcome! Feel free to open issues or pull requests for any improvements or new features.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author
[MAUSAM GAIKWAD](https://github.com/MausamGaikwad)

## Acknowledgments
* This project is inspired by the course/tutorial by Angela Yu on [Udemy](https://www.udemy.com).
* Special thanks to Angela Yu for the valuable instruction and guidance.
* Icons made from a third-party resource (e.g., icon packs, websites). Ensure to comply with the usage terms and conditions.
