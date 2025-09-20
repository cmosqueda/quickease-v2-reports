This master catalog lists all test cases for `EMAIL SERVICE -> ESxxx` module.

---

## In list format:

- **ES001: Forgot password email service**

  - Description: The email template for "Forgot Password" mechanism should take the user to the "auth change password" screen. It should ask user to fill in the required inputs (new password, confirm new password).
  - Steps to perform:
    1. Request for forgot password via login screen
    2. Access the sent email service template on the registered email's inbox.

- **ES002: Request password change email service**

  - Description: For this, the user needs to be logged in and authenticated first. The email template for "Request change password" button found on both the user's account settings or manually sent by the admin should take the user to the "auth change password" screen. It should ask user to fill in the required inputs (new password, confirm new password).
  - Steps to perform:
    1. Request for password change via user settings. Or, have the admin send the email service for password change.
    2. Access the sent email service template on the registered email's inbox.

- **ES003: Verify email address email service**
  - Description: The email template for "Request email change" button found on both the account settings (user side) or manually sent by the admin should take the user to the "auth verify email" screen. The screen should display the account email, along with the associated token, and a "verify email" button. Clicking the "verify email" button should verify the email and navigate user back to the login page.
  - Steps to perform:
    1. Request for email verification via user settings. Or, have the admin send the email service for email verification.
    2. Access the sent email service template on the registered email's inbox.

---

## In tabular format:

| FEAT_CODE | Feature Name                          | Description                                                                                                                                      |
| --------- | ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| ES001     | Forgot password email service         | The email template for "Forgot Password" should take the user to the "auth change password" screen, where they enter a new password and confirm. |
| ES002     | Request password change email service | Requires the user to be logged in. The email template for "Request change password" should take the user to the "auth change password" screen.   |
| ES003     | Verify email address email service    | The email template for "Request email change" should take the user to the "auth verify email" screen, where the user can verify their email.     |
