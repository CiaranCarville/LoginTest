This project will be a standard login system.
My intentions are to improve my back-end coding abilities as they are currently my weakest point.

The project will be made up of multiple parts.
User Registration:

Allow users to create an account by providing necessary information such as username, email, and password.
Perform validation and ensure data integrity for the registration process.
Store user account details securely in a database.
User Authentication:

Verify the identity of users during the login process.
Validate user credentials (username/email and password) against stored data.
Use secure password hashing techniques (e.g., bcrypt) to store passwords in a protected format.
Manage user sessions to keep users logged in across multiple requests.
Password Reset:

Provide a mechanism for users to reset their forgotten passwords.
Implement a password reset workflow that includes generating and sending a password reset link or temporary password to the user's registered email.
Validate the reset request and allow users to securely set a new password.
User Profile Management (optional):

Allow users to view and update their profile information.
Provide functionality to edit personal details, change passwords, update profile pictures, and manage account settings.
Access Control:

Implement role-based or permission-based access control to restrict certain functionalities or content based on user roles or privileges.
Ensure that sensitive areas of the application are only accessible to authenticated users.
Security Measures:

Implement measures to protect against common security threats, such as cross-site scripting (XSS) and cross-site request forgery (CSRF).
Use secure protocols (e.g., HTTPS) to encrypt data transmission over the network.
Employ techniques like input validation, output encoding, and parameterized queries to prevent SQL injection attacks.
Logging and Monitoring (optional):

Implement logging functionality to record login attempts, errors, and other relevant events.
Monitor and analyze logs to identify suspicious activities or security breaches.
User Feedback and Notifications (optional):

Provide feedback to users during the login process, such as displaying appropriate error messages for invalid credentials or account lockouts.
Send notifications to users for successful login, password changes, or other important account-related activities.
