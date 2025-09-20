This master catalog lists all test cases for `AUTH -> Axxx` module.

---

## In list format:

- **A001: Login**

  - Description: The user should be able to log in with registered user credentials.
  - Steps to perform:
    1. On the landing page, click on the sign in button. This should take user on the login/signin screen.
    2. Enter the necessary credentials like the email and password.
    3. Click on the login bar button.

- **A002: Signup**

  - Description: The user should be able to sign up with required details (first name, last name, email address, password, confirm password) and accept the application’s terms and conditions.
  - Steps to perform:
    1.  On the landing page, click on the join now button. This should take user on the register/sign up screen.
    2.  Enter the required account details for account creation, such as the first name, last name, email and password.
    3.  Accept the terms and conditions.
    4.  Click on the register bar button.

- **A003: Reset Password**

  - Description: The user should be able to reset their password, typically through an email service.
  - Steps to perform:
    1. Make sure the user account was already logged in and email is verified.
    2. On the settings menu, select **the request for password change** setting. This should trigger the email service to send a password change request on your registered email.
    3. Go to your registered email's inbox. Look for an email sent by QuickEase's email service and access it. This should direct user to a **reset password screen** to process password reset.
    4. On the **reset password screen**, enter the required data like the new password.
    5. Click on the verify bar button to confirm password reset.

- **A004: Logout**

  - Description: The user should be able to log out of their account.
  - Steps to perform:
    1. Make sure the user account was already logged in.
    2. On the drawer navigation, click on the logout button.

- **A005: Forgot Password**
  - Description: The user should be able to reset a forgotten password.
  - Steps to perform:
    1. On the login screen, click on the **forgot password** link text.
    2. Provide the registered email address to send the password reset request. Then, click on the request bar button to confirm the action.
    3. Go to your registered email's inbox. Look for an email sent by QuickEase's email service adn access it. This should direct user to a **reset password screen** to process password reset.
    4. On the **reset password screen**, enter the required data like the new password.
    5. Click on the verify bar button to confirm password reset.

---

## In tabular format:

| FEAT_CODE | Feature Name    | Description                                                                                    |
| --------- | --------------- | ---------------------------------------------------------------------------------------------- |
| A001      | Login           | The user should be able to log in with registered user credentials.                            |
| A002      | Signup          | The user should be able to sign up with details and accept the application’s terms/conditions. |
| A003      | Reset Password  | The user should be able to reset their password, typically through an email service.           |
| A004      | Logout          | The user should be able to log out of their account.                                           |
| A005      | Forgot Password | The user should be able to reset a forgotten password.                                         |
