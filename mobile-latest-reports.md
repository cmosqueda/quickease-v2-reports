# CONSOLIDATED LATEST REPORTS FOR MOBILE

_All contents in this section are the consolidated TLDRs from each test categories in mobile. This will be updated for every test iterations._

**Last Updated:** Sept. 27, 2025

---

## MOBILE TESTS IN LIST FORMAT

[**AUTH**](./mobile/auth/sept-27-2025.md)

- ✅ A001: Login – Functional; password peek option for password field suggested for better UX.
- ✅ A002: Signup – Functional; password peek option for password field suggested for better UX.
- ✅ A003: Logout – Remains functional.

[**FLASHCARDS**](./mobile/flashcards/sept-27-2025.md)

- ✅ FL001: Create a flashcard set manually – Passed, fixes from last test implemented (floating button, CRUD, seamless previews, hidden create button)
- ✅ FL002: View a flashcard set – Passed, viewing works as expected (no regressions).
- ✅ FL003: Edit/update a flashcard set – Passed; can now perform CRUD on cards.
- ✅ FL004: Delete a flashcard set – Remained passed and functional
- ✅💡 FL005: Change flashcard set visibility – Passed; private cards now restrict other users from access/viewing. Recommends implementing a label indicator in library to know if flashcard set is public or private.
- ✅ FL006: Generate a flashcard set from note – Remained passed and functional
- ✅ FL007: Generate a flashcard set from PDF – Remained passed and functional
- ✅ FL008: Search a flashcard set – Remained passed and functional
- ✅💡 FL009: Share a flashcard via URL copy – Passed and functional, link can only be accessed via web platform. Recommends disabling share link option if flashcard is private.
- ⚠️ GENERAL ISSUE ON FLASHCARDS: Navigation flow is faulty.

[**FORUMS**](./mobile/forums/sept-27-2025.md)

- ✅ FO001: Read/view forum posts – Passed; no regressions
- ✅ FO002: Search posts on forums – Passed; no regressions
- ✅ FO003: Create a post – Passed; no regressions
- ✅ FO004: Post attachments – Passed with suggestions needed: Only show attachment options for **public** notes, flashcards, and quizzes.
- ✅ FO005: Edit/update a post – Passed; no regressions
- ✅⚠️ FO006: Delete a post – Passed with refinements needed; suggest moving delete button and adding confirmation pop-up
- ✅ FO007: Upvote/downvote post – Passed; issue on full post voting fixed
- ✅⚠️ FO008: Comment on a post – Passed with refinements needed; apply QuickEase Gabarito font for consistency
- ✅ FO009: Threaded replies on comments – Passed; no regressions
- ✅ FO010: Upvote/downvote comment – Passed; no regressions
- ✅ FO011: Edit comment – Passed; no regressions
- ✅ FO012: Notifications – Passed; Issue on viewing notifs for threaded replies now fixed.
- 🚧 FO013: Report a post/comment – Not yet implemented
- 🚧 FO014: Share a forum post via URL copy – Not yet implemented

[**NAVIGATION**](./mobile/navigation/sept-27-2025.md)

- ✅ NAV001: Navigation after login – Passed; back button now exits app instead of returning user back to login screen.
- ✅ NAV002: Drawer navigation – Passed; Navigation flow across screens now functioning seamlessly
- ✅ NAV003: Topside tab navigation (Flashcards/Notes/Quizzes) – Remained passed; no regressions.
- 🚧 NAV004: Deep linking – Not yet implemented; only available on web.
- ✅ NAV005: Logout navigation flow – Passed; remains functional and restricts return to authenticated routes.
- ✅ NAV006: Error/fallback navigation – Passed; functional
- ✅ NAV007: Automatic login for saved session – Passed; functional

[**NOTES**](./mobile/notes/sept-27-2025.md)

- ✅💡 N001: Create a note manually – Passed; Recommends applying QuickEase Gabarito font on rich text editor
- ✅ N002: View a note – Passed; remained functional, no regressions.
- ✅ N003: Edit/update a note – Passed; remained functional, no regressions.
- ✅ N004: Delete a note – Passed; remained functional, no regressions.
- ✅💡 N005: Change a note visibility – Passed; private notes now restrict other users from access/viewing. Recommends implementing a label indicator in library to know if flashcard set is public or private.
- ✅💡 N006: Generate a note summary from PDF – Passed; Recommends applying QuickEase Gabarito font on rich text editor
- ✅💡 N007: Generate a note summary from Image – Passed; Recommends applying QuickEase Gabarito font on rich text editor
- ✅ N008: Search a note – Passed; functional, no issues.
- ✅💡 N009: Share a note via URL copy – Passed; Recommends disabling option if note is private.
- ⚠️ GENERAL ISSUE ON NOTES: Navigation flow is faulty.

[**POMODORO**](./mobile/pomodoro/sept-27-2025.md)

- ✅ PT001: Customize time intervals – Remained passed and functional;
- ✅ PT002: Enabling/disabling Pomodoro drawer display – Remained passed and functional;
- ✅ PT003: Full timer display – Remained passed and functional;
- ✅ PT004: Timer operation – Remained passed and functional;

[**PROFILE**](./mobile/profile/sept-27-2025.md)

- ✅💡 PF001: View own profile – Passed; functional but refinements needed for viewing user’s posts (suggested UI improvements).
- ❌ PF002: View other user's profile – Failed; Other users' profile details (stats, posts) does not show.

[**QUIZZES**](./mobile/quizzes/sept-27-2025.md)

- ⚠️ Q001: Create a quiz manually – Issue detected; UI bug in "add question" button. Displays persistently at Title and Description screen.
- ✅ Q002: Answer a quiz – Stable (no regression).
- ✅ Q003: Review a quiz – Stable (no regression).
- ✅ Q004: View all user attempts history – Stable (no regression).
- ✅ Q005: Answer a shared quiz in forums – Stable (no regression).
- ✅ Q006: View leaderboard rank of a shared quiz – Stable (no regression).
- ✅ Q007: Edit/update a quiz – Stable (no regression).
- ✅ Q008: Delete a quiz – Stable (no regression).
- ✅💡 Q009: Change a note visibility – Passed; private notes now restrict other users from access/viewing. Recommends implementing a label indicator in library to know if flashcard set is public or private.
- ✅ Q010: Generate a quiz from note – Stable (no regression).
- ✅ Q011: Generate a quiz from PDF – Stable (no regression).
- ✅ Q012: Search a quiz – Stable (no regression).
- ✅💡 Q013: Share a quiz via URL copy – Passed; Recommends disabling option if quiz is private.
- ⚠️ GENERAL ISSUE ON QUIZZES: Navigation flow is faulty.

[**SETTINGS**](./mobile/settings/sept-27-2025.md)

- ⚠️ ST001: Change theme – Functional, but issue detected with system dark/light mode toggle (disappears after multiple switches).
- ✅ ST002: Change email address – Passed; functional but needs to enforce change limits.
- ✅ ST003: Verify email address – Passed; still functional
- ✅ ST004: Change name – Passed; functional but needs to enforce change limits.
- ✅ ST005: Change profile visibility – Passed; still functional
- ✅ ST006: Reset password – Passed; functional (web only, no mobile screen).

---

## MOBILE TESTS IN TABULAR FORMAT

| Module         | Test ID | Status | Summary                                                                                                       |
| -------------- | ------- | ------ | ------------------------------------------------------------------------------------------------------------- |
| **AUTH**       | A001    | ✅     | Login functional; password peek suggested for better UX                                                       |
|                | A002    | ✅     | Signup functional; password peek suggested for better UX                                                      |
|                | A003    | ✅     | Logout remains functional                                                                                     |
| **FLASHCARDS** | FL001   | ✅     | Create flashcard set manually – Fixes from last test implemented (floating button, CRUD, seamless previews)   |
|                | FL002   | ✅     | View flashcard set – Passed; no regressions                                                                   |
|                | FL003   | ✅     | Edit/update flashcard set – Passed; can now perform CRUD on cards                                             |
|                | FL004   | ✅     | Delete flashcard set – Remains functional                                                                     |
|                | FL005   | ✅💡   | Change flashcard set visibility – Passed; private cards restricted, suggest indicator for public/private sets |
|                | FL006   | ✅     | Generate flashcard set from note – Remains functional                                                         |
|                | FL007   | ✅     | Generate flashcard set from PDF – Remains functional                                                          |
|                | FL008   | ✅     | Search flashcard set – Remains functional                                                                     |
|                | FL009   | ✅💡   | Share flashcard via URL copy – Passed; link web-only, suggest disabling option if private                     |
| **FORUMS**     | FO001   | ✅     | Read/view forum posts – Passed; no regressions                                                                |
|                | FO002   | ✅     | Search posts – Passed; no regressions                                                                         |
|                | FO003   | ✅     | Create a post – Passed; no regressions                                                                        |
|                | FO004   | ✅     | Post attachments – Passed; suggest only allow public items as attachments                                     |
|                | FO005   | ✅     | Edit/update a post – Passed; no regressions                                                                   |
|                | FO006   | ✅⚠️   | Delete a post – Passed; refinements suggested (move button, add confirmation pop-up)                          |
|                | FO007   | ✅     | Upvote/downvote post – Passed; full post voting issue fixed                                                   |
|                | FO008   | ✅⚠️   | Comment on post – Passed; suggest applying QuickEase Gabarito font for consistency                            |
|                | FO009   | ✅     | Threaded replies – Passed; no regressions                                                                     |
|                | FO010   | ✅     | Upvote/downvote comment – Passed; no regressions                                                              |
|                | FO011   | ✅     | Edit comment – Passed; no regressions                                                                         |
|                | FO012   | ✅     | Notifications – Passed; threaded replies issue fixed                                                          |
|                | FO013   | 🚧     | Report post/comment – Not yet implemented                                                                     |
|                | FO014   | 🚧     | Share forum post via URL copy – Not yet implemented                                                           |
| **NAVIGATION** | NAV001  | ✅     | Navigation after login – Passed; back button now exits app instead of returning to login                      |
|                | NAV002  | ✅     | Drawer navigation – Passed; seamless across screens                                                           |
|                | NAV003  | ✅     | Topside tab navigation – Passed; no regressions                                                               |
|                | NAV004  | 🚧     | Deep linking – Not yet implemented (web only)                                                                 |
|                | NAV005  | ✅     | Logout navigation – Passed; restricts return to authenticated routes                                          |
|                | NAV006  | ✅     | Error/fallback navigation – Passed; functional                                                                |
|                | NAV007  | ✅     | Automatic login for saved session – Passed; functional                                                        |
| **NOTES**      | N001    | ✅💡   | Create note manually – Passed; suggest applying QuickEase Gabarito font on rich text editor                   |
|                | N002    | ✅     | View note – Passed; no regressions                                                                            |
|                | N003    | ✅     | Edit/update note – Passed; no regressions                                                                     |
|                | N004    | ✅     | Delete note – Passed; no regressions                                                                          |
|                | N005    | ✅💡   | Change note visibility – Passed; private notes restricted, suggest label indicator for public/private         |
|                | N006    | ✅💡   | Generate summary from PDF – Passed; suggest applying QuickEase Gabarito font on rich text editor              |
|                | N007    | ✅💡   | Generate summary from Image – Passed; suggest applying QuickEase Gabarito font on rich text editor            |
|                | N008    | ✅     | Search note – Passed; no issues                                                                               |
|                | N009    | ✅💡   | Share note via URL copy – Passed; suggest disabling option if private                                         |
| **POMODORO**   | PT001   | ✅     | Customize time intervals – Remains functional                                                                 |
|                | PT002   | ✅     | Pomodoro drawer display toggle – Remains functional                                                           |
|                | PT003   | ✅     | Full timer display – Remains functional                                                                       |
|                | PT004   | ✅     | Timer operation – Remains functional                                                                          |
| **PROFILE**    | PF001   | ✅💡   | View own profile – Passed; refinements suggested for viewing posts (UI improvements)                          |
|                | PF002   | ❌     | View other user’s profile – Failed; stats and posts not showing                                               |
| **QUIZZES**    | Q001    | ⚠️     | Create quiz manually – Issue detected; “add question” button persists at Title/Description screen             |
|                | Q002    | ✅     | Answer quiz – Passed; no regressions                                                                          |
|                | Q003    | ✅     | Review quiz – Passed; no regressions                                                                          |
|                | Q004    | ✅     | View all attempts history – Passed; no regressions                                                            |
|                | Q005    | ✅     | Answer shared quiz – Passed; no regressions                                                                   |
|                | Q006    | ✅     | View leaderboard rank – Passed; no regressions                                                                |
|                | Q007    | ✅     | Edit/update quiz – Passed; no regressions                                                                     |
|                | Q008    | ✅     | Delete quiz – Passed; no regressions                                                                          |
|                | Q009    | ✅💡   | Change quiz visibility – Passed; private quizzes restricted, suggest label indicator for public/private       |
|                | Q010    | ✅     | Generate quiz from note – Passed; no regressions                                                              |
|                | Q011    | ✅     | Generate quiz from PDF – Passed; no regressions                                                               |
|                | Q012    | ✅     | Search quiz – Passed; no issues                                                                               |
|                | Q013    | ✅💡   | Share quiz via URL copy – Passed; suggest disabling option if private                                         |
| **SETTINGS**   | ST001   | ⚠️     | Change theme – Passed but bug with system dark/light toggle disappearing after multiple switches              |
|                | ST002   | ✅     | Change email address – Passed; needs to enforce change limits                                                 |
|                | ST003   | ✅     | Verify email address – Passed; functional                                                                     |
|                | ST004   | ✅     | Change name – Passed; needs to enforce change limits                                                          |
|                | ST005   | ✅     | Change profile visibility – Passed; functional                                                                |
|                | ST006   | ✅     | Reset password – Passed (web only, no mobile screen)                                                          |
