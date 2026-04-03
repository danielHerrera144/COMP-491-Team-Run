## Sensitive Data
The app stores:
  - email addresses
  - encrypted passwords
  - workout history
  - water intake logs

Passwords are protected using bcrypt hashing.

## Authentication
The system uses JSON Web Tokens (JWT).

## Possible Attacks
Possible risks:
  - injection attacks
  - cross site scripting
  - unauthorized API requests

The server validates user input before saving it.

## Security Practices
Security measures used:
  - bcrypt password hashing
  - JWT authentication
  - input validation
  - MongoDB Atlas secure database hosting
