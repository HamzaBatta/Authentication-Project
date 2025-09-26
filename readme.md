# Node.js Authentication Project

A simple authentication app built with Node.js, Express, MongoDB, Passport.js, and EJS.  
Features include user registration, login, password reset via email, and session management.

## Features

- User signup and login
- Password reset via email (Gmail SMTP with app password)
- Flash messages for feedback
- Session-based authentication
- Dashboard for logged-in users

## Setup

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Configure environment variables:  
   Create a `config.env` file in the root directory with:
   ```
   PORT=3000
   DATABASE_LOCAL=mongodb://localhost:27017/users
   GMAIL_EMAIL=your_gmail_address@gmail.com
   GMAIL_PASSWORD=your_gmail_app_password
   ```

4. Start the app:
   ```
   npm start
   ```

## Usage

- Visit `http://localhost:3000` in your browser.
- Register a new account, login, and test password reset.

## License
MIT