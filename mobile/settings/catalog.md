This master catalog lists all test cases for `SETTINGS -> STxxx` module.

---

## In list format:

- **ST001: Change theme**

  - Description: The user should be able to change the application's theme.
  - Steps to perform:
    1. On the drawer navigation, click on the settings button.
    2. Look for customizations category, and select the set theme option.
    3. Select your desired theme to be applied.

- **ST002: Change email address**

  - Description: The user should be able to change their account's binded email address.
  - Steps to perform:
    1. On the drawer navigation, click on the settings button.
    2. Look for account category, and select the change your email option.
    3. Enter your new email address. Make sure that it is a valid address.

- **ST003: Verify email address**

  - Description: The user should be able to verify their email sent to them.
  - Steps to perform:
    1. For this, make sure that the logged in account is not yet verified.
    2. On the drawer navigation, click on the settings button.
    3. Look for account category, and select the verify email option. This will send an email service to your registered email address account.
    4. Go to your registered email's inbox and look for the email service sent to you by the QuickEase's email bot.
    5. Access the service. This will direct you to the email verification screen process.
    6. Verify your account email by clicking on the verify button.

- **ST004: Change name**

  - Description: The user should be able to change their full display name.
  - Steps to perform:
    1. On the drawer navigation, click on the settings button.
    2. Look for account category, and select the change your name option.
    3. Enter your new first name and last name.

- **ST005: Change profile visibility**

  - Description: The user should be able to change their profile visibility by turning on or off the profile visibility configuration.
  - Steps to perform:
    1. On the drawer navigation, click on the settings button.
    2. Look for privacy category, and toggle the profile visibility option.

- **ST006: Reset Password**

  - Description: The user should be able to reset their password, typically through an email service.
  - Steps to perform:
    1. On the drawer navigation, click on the settings button.
    2. On the settings menu, look for account category and select **the request for password change** setting. This should trigger the email service to send a password change request on your registered email.
    3. Go to your registered email's inbox. Look for an email sent by QuickEase's email service and access it. This should direct user to a **reset password screen** to process password reset.
    4. On the **reset password screen**, enter the required data like the new password.
    5. Click on the verify bar button to confirm password reset.

---

## In tabular format:

| FEAT_CODE | Feature Name              | Description                                                                          |
| --------- | ------------------------- | ------------------------------------------------------------------------------------ |
| ST001     | Change theme              | The user should be able to change the application's theme.                           |
| ST002     | Change email address      | The user should be able to change their account's binded email address.              |
| ST003     | Verify email address      | The user should be able to verify their email sent to them.                          |
| ST004     | Change name               | The user should be able to change their full display name.                           |
| ST005     | Change profile visibility | The user should be able to change their profile visibility configuration.            |
| ST006     | Reset password            | The user should be able to reset their password, typically through an email service. |
