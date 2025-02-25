Login Page

This project consists of a simple login page with HTML, JavaScript, and an API call for authentication.

Files

index.html: The main login page containing the form for username and password input.

login.js: JavaScript file that handles form submission and API interaction.

Features

Prevents empty username and password submission.

Sends login credentials to the API (/api/login) using a POST request.

Displays error messages for invalid inputs or login failures.

Redirects to dashboard.html upon successful login.

Installation and Setup

Clone the repository:

git clone https://github.com/yourusername/your-repository.git
cd your-repository

Ensure you have a backend API running at /api/login that handles authentication.

Open index.html in a browser to test the login functionality.

Usage

Enter a username and password.

Click the "Login" button.

If credentials are correct, the page redirects to dashboard.html.

If login fails, an error message is displayed.

API Endpoint

POST /api/login

Request Body:

{
    "username": "example_user",
    "password": "example_password"
}

Response (Success):

{
    "message": "Login successful"
}

Response (Failure):

{
    "message": "Invalid username or password"
}

Contributing

If you want to contribute, feel free to submit a pull request!

License

This project is open-source under the MIT License.

