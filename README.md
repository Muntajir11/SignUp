# SignUp 

## Description

This project is a secure backend application built for user authentication using Node.js, Express.js, and PostgreSQL. User passwords are stored using bcrypt, a secure hashing algorithm that incorporates salting to protect against password cracking attempts. With its emphasis on security and robust authentication mechanisms, this project provides a solid foundation for building secure web applications.


## Features

- User Registration: Users can sign up with a unique email address and password.
- User Authentication: Passwords are securely hashed using bcrypt. Authentication is implemented using Passport.js with a local strategy for email/password authentication and Google OAuth2 strategy for Google authentication.
- Session Management: Sessions are managed using express-session with session data stored in the PostgreSQL database.
- User Interface: The front-end interface is built using HTML, CSS, and EJS templates.

## Demo

https://github.com/Muntajir11/SignUp/assets/91109805/c9856a83-d041-49f3-a489-a3b2ac2e3fa5

## Installation

1. Clone the repository: git clone  https://github.com/Muntajir11/SignUp.git 
2. Install dependencies:
--> cd SignUp [Go to the folder where it was cloned]
--> npm install
  
3. Set up environment variables:

Create a `.env` file in the project root directory and add the following environment variables:
PG_USER=your_postgres_username <br />
PG_PASSWORD=your_postgres_password <br />
PG_DATABASE=your_database_name <br />
PG_HOST=your_postgres_host <br />
PG_PORT=your_postgres_port <br />
SESSION_SECRET=your_session_secret <br />
GOOGLE_CLIENT_ID=your_google_client_id <br />
GOOGLE_CLIENT_SECRET=your_google_client_secret <br />


Replace `your_postgres_username`, `your_postgres_password`, `your_database_name`, `your_postgres_host`, `your_postgres_port` with your PostgreSQL database credentials, and `your_session_secret`, `your_google_client_id`, `your_google_client_secret` with your own secret keys.

4. Create PostgreSQL Database:

You need to create a PostgreSQL database with the provided credentials. Refer to the PostgreSQL documentation for instructions on creating a database.

5. Run the application: node index.js
6. The application will be running on http://localhost:3000 by default.

## Usage

1. Open your web browser and go to http://localhost:3000.
2. Sign up for a new account or log in with existing credentials.
3. After successful authentication, you will be redirected to the welcome page.
4. Click on the "Logout" button to log out of the application.

## Contributing

Contributions are welcome! If you find any bugs or want to suggest new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.








