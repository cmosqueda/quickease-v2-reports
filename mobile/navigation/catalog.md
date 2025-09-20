This master catalog lists all test cases for `NAVIGATION -> NAVxxx` module.

**Note:** Each test case in this module does not include detailed steps like other modules. Instead, these tests focus solely on validating the quality and consistency of the mobile navigation flow.

---

## In list format:

- **NAV001: Navigation after login**

  - Description: After successful login, pressing the system back button should not return the user to the authentication screens (login/register) unless they explicitly log out. Expected behavior is either to remain on the dashboard or exit the app.

- **NAV002: Drawer navigation**

  - Description: The user should be able to open the drawer and navigate between different modules without state loss.

- **NAV003: Topside tab navigation (Flashcards/Notes/Quizzes)**

  - Description: The user should be able to switch between topside navigation categories (e.g., All, By Recent, AI-generated) without losing state or causing reload errors.

- **NAV004: Deep linking**

  - Description: The user should be able to open the app directly to a specific screen using a deep link (e.g., shared quiz link, forum post link).

- **NAV005: Logout navigation flow**

  - Description: After logging out, the user should be redirected to the login screen and prevented from going back to authenticated routes via the back button.

- **NAV006: Error/fallback navigation**

  - Description: If the user attempts to navigate to an invalid or unavailable route, the app should display an error or redirect to a safe screen (e.g., dashboard).

- **NAV007: Automatic login for saved session**
  - Description: If the user has logged in previously and did not opt to log out the account, the account should be automatically logged in the next time the user opens the app again.

---

## In tabular format:

| FEAT_CODE | Feature Name                       | Description                                                                                                                                                                                                                                       |
| --------- | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| NAV001    | Navigation after login             | After successful login, pressing the system back button should not return the user to the authentication screens (login/register) unless they explicitly log out. Expected behavior is either to remain on the dashboard or exit the app. screen. |
| NAV002    | Drawer navigation                  | User can open the drawer and navigate between modules without state loss.                                                                                                                                                                         |
| NAV003    | Topside tab navigation             | Switching between "All", "By Recent", and "AI-generated" inside modules should work without state loss.                                                                                                                                           |
| NAV004    | Deep linking                       | App should support deep links to specific screens.                                                                                                                                                                                                |
| NAV005    | Logout navigation flow             | After logout, user should be redirected to login and prevented from back navigation to private screens.                                                                                                                                           |
| NAV006    | Error/fallback navigation handling | Invalid or unavailable routes should redirect to a safe/default screen.                                                                                                                                                                           |
| NAV007    | Automatic login for saved session  | If the user has logged in previously and did not opt to log out the account, the account should be automatically logged in the next time the user opens the app again.                                                                            |
