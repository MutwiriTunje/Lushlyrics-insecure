# Lushlyrics Authentication Integration

## Overview

This project implements a user authentication system for Lushlyrics, enhancing access security and providing a seamless registration and login experience for users. Utilizing Auth0's OpenID Connect (OIDC), this solution allows users to easily create accounts, log in, and recover passwords while ensuring secure access to the Lushlyrics website.

## Features

- User registration, login, and logout functionalities.
- Password recovery through email verification.
- Redirect to Auth0 login page for authentication.
- Welcome page with options to visit the Lushlyrics website or log out.

## Setup

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd lushlyrics-auth-integration

Create a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install requirements:

pip install -r requirements.txt
Set up Auth0:

Create an Auth0 account and set up a new application.
Obtain your Auth0 credentials and add them to a .env file in the root directory.
Update settings.py:

Ensure that Auth0 settings and other configurations are properly added.
Run the server:

python manage.py runserver

Usage
Upon running the server, navigate to http://127.0.0.1:8000/ to access the welcome page.
Users can choose to visit the Lushlyrics website, which redirects to the Auth0 login page for authentication.
After successful verification, users are taken directly to the Lushlyrics website.
Conclusion
This project successfully integrates Auth0 authentication into the Lushlyrics platform, meeting the objectives of secure user access and improved account management. The implementation is designed to enhance user experience and provide a robust solution for managing user credentials.
