# Password Strength Checker

A simple Python program that checks the strength of a password based on different security criteria.

## Features

- Checks password length
- Detects uppercase letters
- Detects lowercase letters
- Detects numbers
- Detects special characters
- Displays password strength:
  - Weak
  - Medium
  - Strong

## Technologies Used

- Python
- Regular Expressions (`re` module)

## How It Works

The program evaluates the password using the following rules:

| Criteria | Condition |
|---|---|
| Length | Minimum 8 characters |
| Uppercase | At least 1 uppercase letter |
| Lowercase | At least 1 lowercase letter |
| Number | At least 1 digit |
| Special Character | At least 1 special symbol |

## Example

```bash
Enter your password: Umar@123
Password Strength: Strong Password 💪
