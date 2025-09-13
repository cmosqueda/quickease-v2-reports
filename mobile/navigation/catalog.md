This master catalog lists all test cases for `NAVIGATION -> NAVxxx` module.

---

## In list format:

- **NAV001: Navigation after login**

  > After successful login, pressing the system back button should not return the user to the authentication screen. Expected behavior is either to remain on the dashboard or exit the app.

- **NAV002: Protected route access**

  > The user should not be able to navigate back to authentication screens (login/register) once logged in, unless they explicitly log out.

- **NAV003: Drawer navigation**

  > The user should be able to open the drawer and navigate between different modules without state loss.

- **NAV004: Topside tab navigation (Flashcards/Notes/Quizzes)**

  > The user should be able to switch between topside navigation categories (e.g., All, By Recent, AI-generated) without losing state or causing reload errors.

- **NAV005: Deep linking**

  > The user should be able to open the app directly to a specific screen using a deep link (e.g., shared quiz link, forum post link).

- **NAV006: Logout navigation flow**

  > After logging out, the user should be redirected to the login screen and prevented from going back to authenticated routes via the back button.

- **NAV007: Forward navigation state**

  > Navigating from one screen to another should properly maintain the state when navigating forward.

- **NAV008: Error/fallback navigation**
  > If the user attempts to navigate to an invalid or unavailable route, the app should display an error or redirect to a safe screen (e.g., dashboard).

---

## In tabular format:

| FEAT_CODE | Feature Name                       | Description                                                                                                      |
| --------- | ---------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| NAV001    | Navigation after login             | After successful login, pressing the system back button should not return the user to the authentication screen. |
| NAV002    | Protected route access             | User should not be able to navigate back to auth screens once logged in, unless explicitly logged out.           |
| NAV003    | Drawer navigation                  | User can open the drawer and navigate between modules without state loss.                                        |
| NAV004    | Topside tab navigation             | Switching between "All", "By Recent", and "AI-generated" inside modules should work without state loss.          |
| NAV005    | Deep linking                       | App should support deep links to specific screens.                                                               |
| NAV006    | Logout navigation flow             | After logout, user should be redirected to login and prevented from back navigation to private screens.          |
| NAV007    | Forward navigation state           | State should persist when navigating forward between screens.                                                    |
| NAV008    | Error/fallback navigation handling | Invalid or unavailable routes should redirect to a safe/default screen.                                          |
