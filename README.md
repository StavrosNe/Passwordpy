Sure! Here's the same text formatted using Markdown:

# Password Manager Application

This is a small password manager application that I created as a hobby project to learn new things using Python. The application allows users to store and manage their passwords securely using encryption and hashing.

## Features

- User sign-up and login
- Data encryption using AES 256 CBC and unique IV for each data entry
- Password hashing using salt and pepper
- Connection to websites through the app
- Strong password and encryption key requirements

## Requirements

- Python 3.x
- Pillow==9.5.0
- pycryptodome==3.17
- customtkinter==5.1.2
- googlesearch-python==1.2.3

## Installation

1. Clone the repository to your local machine.
2. Install the required libraries using pip: `pip install -r requirements.txt`.
3. Run the application using the command `python password_manager.py`.

## Usage

1. Sign up for an account using the application.
2. Log in to your account using your username and password.
3. Enter a strong encryption key to protect your data.
4. Add new passwords by entering the application name, username, and password.
5. Connect to websites through the app by entering the website URL and clicking "Connect".

## Security

- Passwords are stored hashed in a local database using salt and pepper.
- Data is encrypted using AES 256 CBC and unique IV for each data entry.
- The encryption key is not stored anywhere and must be entered by the user.
- Passwords and encryption keys must meet strong requirements for length and complexity.

## Limitations

- The number of passwords that can be stored is limited by the local database size.
- Some websites may not be compatible with the app's website connection feature.

## Future Work

In the future, I plan to add the following features:

- Two-factor authentication for added security
- Automatic password generation using a secure algorithm
- Integration with popular web browsers for easier website connection
