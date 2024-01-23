## About Laravel Auth API
Laravel Auth API is authentication system using laravel sanctum. This webAPI has features listed below:

- Register API to register user with first_name, last_name, email, password, password_confirm
- Login API to login user with the credentials, jwt token will be generated and stored in the cookie for 1 day
- Logout API to logut the user
- User API to go to the authenticated user route after login
- Forgot password API to send the password reset link with the reset token
- Reset password API to reset the password for the email

## Routes List
- POST 127.0.0.1:8000/api/register 
- POST 127.0.0.1:8000/api/login 
- GET 127.0.0.1:8000/api/user 
- POST 127.0.0.1:8000/api/logout 
- POST 127.0.0.1:8000/api/forgot 
- POST 127.0.0.1:8000/api/reset

Headers include: X-Requested-With: XMLHttpRequest