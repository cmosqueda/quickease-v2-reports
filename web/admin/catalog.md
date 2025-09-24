This master catalog lists all test cases for `ADMIN -> ADMINxxx` module.

---

## In list format:

- **ADMIN001: Login**

  - Description: The admin should be able to login and access the admin dashboard.
  - Steps to perform:
    1. On the landing page, click on the sign in button. This should direct on the login/signin screen.
    2. Enter the admin credentials.
    3. Click on the login bar button.

- **ADMIN002: User search**

  - Description: The admin should be able to search for a user by its user name.
  - Steps to perform:
    1. On user management, click on the search bar.
    2. Enter an existing user's name on the field.

- **ADMIN003: View user account details**

  - Description: The admin should be able to view the user's account details.
  - Steps to perform:
    1. On user management, select on any of the user accounts.

- **ADMIN004: Update user account details**

  - Description: The admin should be able to update a user's account details.
  - Steps to perform:
    1. On user management, select on any of the user accounts.
    2. Under the account information form, click on the edit button.
    3. Update the account's details by editing any of its information.
    4. Save the edits by clicking the update button. Else, cancel the edits by clicking on the cancel button.

- **ADMIN005: Delete user account**

  - Description: The admin should be able to delete user's account.
  - Steps to perform:
    1. On user management, select on any of the user accounts.
    2. Expand the other options menu.
    3. Click on the delete account button.

- **ADMIN006: Send change password email service**

  - Description: The admin should be able to send a password reset email to the user's registered email address.
  - Steps to perform:
    1. On user management, select on any of the user accounts.
    2. Expand the other options menu.
    3. Click on the send an email to change password button.

- **ADMIN007: Send email verification email service**

  - Description: The admin should be able to send an email to the user’s address to verify their account email.
  - Steps to perform:
    1. On user management, select on any of the user accounts.
    2. Expand the other options menu.
    3. Click on the send an email to verify user button.

- **ADMIN008: Delete reported post/comment**

  - Description: Report resolution control: the admin should be able to delete reported posts or comments.
  - Steps to perform:
    1. On report management, select on any of the reports.
    2. Expand the other options menu.
    3. Click on the delete post button.

- **ADMIN009: Delete violator's account**

  - Description: Report resolution control: the admin should be able to delete a violator’s account after multiple violations.
  - Steps to perform:
    1. On report management, select on any of the reports.
    2. Expand the other options menu.
    3. Click on the delete user's account button.

- **ADMIN010: Search a reported post/comment**
  - Description: The admin should be able to search for a reported content by its title or content.
  - Steps to perform:
    1. On report management, click on the search bar.
    2. Enter a title or text content on the field.

---

## In tabular format:

| FEAT_CODE | Feature Name                       | Description                                                                        |
| --------- | ---------------------------------- | ---------------------------------------------------------------------------------- |
| ADMIN001  | Login                              | The admin should be able to login and access the admin dashboard.                  |
| ADMIN002  | User search                        | The admin should be able to search for a user by its user name.                    |
| ADMIN003  | View user account                  | The admin should be able to view the user's account details.                       |
| ADMIN004  | Update user account                | The admin should be able to update a user's account details.                       |
| ADMIN005  | Delete user account                | The admin should be able to delete user's account.                                 |
| ADMIN006  | Send change password email service | The admin should be able to send a password reset email to the user's email.       |
| ADMIN007  | Send email verification            | The admin should be able to send an email to verify the user’s account email.      |
| ADMIN008  | Delete reported post/comment       | The admin should be able to delete reported posts or comments.                     |
| ADMIN009  | Delete violator's account          | The admin should be able to delete a violator’s account after violations.          |
| ADMIN010  | Search a reported post/comment     | The admin should be able to search for a reported content by its title or content. |
