# Feature: User Registration

## Feature Description
Allows new users to create an account on SwiftPay by providing personal details such as full name, phone number, email, and password.

## Functional Goals
- Input fields: Full name, email, phone number, password
- Validate phone number and email format
- Password requirements (min length, special characters)
- Store user data securely
- Redirect to login or dashboard after registration

## Business Value
User registration is the first step for accessing SwiftPay services. This feature ensures only verified users can join the platform.

## User Story
As a new user, I want to register an account with my personal details so that I can start using SwiftPay to send and receive money.

## Acceptance Criteria
- ✅ All required fields are present and validated
- ✅ Duplicate email/phone numbers are rejected
- ✅ Password is securely hashed
- ✅ User is added to the database upon success
- ✅ User is redirected to login screen

## Security Notes
- Store passwords using hashing (e.g., bcrypt)
- Verify input to prevent injection attacks
- Optional: Use OTP or email confirmation before activation
