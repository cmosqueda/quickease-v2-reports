# CONSOLIDATED LATEST REPORTS FOR MOBILE

_All contents in this section are the consolidated TLDRs from each test categories in mobile. This will be updated for every test iterations._

**Last Updated:** Sept. 21, 2025

---

## MOBILE TESTS IN LIST FORMAT

[**AUTH**](./mobile/auth/sept-21-2025.md)

- ✅ A001: Login – Functional; password peek option for password field suggested for better UX.
- ✅ A002: Signup – Functional; password peek option for password field suggested for better UX.
- ✅ A003: Logout – Remains functional.
- ✅⚠️ A004: Forgot Password – Functional; mobile deprecated, to be implemented on web only.

[**FLASHCARDS**](./mobile/flashcards/sept-21-2025.md)

- ✅⚠️ FL001: Create a flashcard set manually – Passed, fixes from last test implemented (floating button, CRUD, seamless previews) but issue remains when no flashcards exist (create button hidden).
- ✅ FL002: View a flashcard set – Passed, viewing works as expected (no regressions).
- ❌ FL003: Edit/update a flashcard set – Failed, can only add new cards; editing/deleting still unsupported.
- ✅ FL004: Delete a flashcard set – Passed, deletion remains functional (no regressions).
- ❌ FL005: Change flashcard set visibility – Failed, visibility toggle works but "private" sets can still be accessed by others.
- ✅ FL006: Generate a flashcard set from note – Passed, generation works; card preview issue from last test now fixed.
- ✅ FL007: Generate a flashcard set from PDF – Passed, generation works; card preview issue from last test now fixed.
- ✅ FL008: Search a flashcard set – Passed, search is functional.

[**FORUMS**](./mobile/forums/sept-21-2025.md)

- ✅ FO001: Read/view forum posts – Passed; no regressions
- ✅ FO002: Search posts on forums – Passed; no regressions
- ✅ FO003: Create a post – Passed; no regressions
- ✅ FO004: Post attachments – Passed; UI refinements for attachment selection added
- ✅ FO005: Edit/update a post – Passed; rich text now works properly
- ✅⚠️ FO006: Delete a post – Passed with refinements needed; suggest moving delete button and adding confirmation pop-up
- ✅ FO007: Upvote/downvote post – Passed; issue on full post voting fixed
- ✅⚠️ FO008: Comment on a post – Passed with refinements needed; apply QuickEase Gabarito font for consistency
- ✅ FO009: Threaded replies on comments – Passed; comment input field now visible
- ✅ FO010: Upvote/downvote comment – Passed; no regressions
- ✅ FO011: Edit comment – Passed; no regressions
- ⚠️ FO012: Notifications – Partial passed; persistent notifs functional but issues remain with threaded replies and missing resolved report notifications
- 🚧 FO013: Report a post/comment – Not yet implemented

[**NAVIGATION**](./mobile/navigation/sept-21-2025.md)

- ❌ NAV001: Navigation after login – Failed; back button still returns user to login instead of exiting app. UX fix required (double back press to exit).
- ❌ NAV002: Drawer navigation – Failed; buggy navigation when accessing shared attachments from forum posts.
- ✅ NAV003: Topside tab navigation (Flashcards/Notes/Quizzes) – Passed; no regressions.
- 🚧 NAV004: Deep linking – Not yet implemented; only available on web.
- ✅ NAV005: Logout navigation flow – Passed; remains functional and restricts return to authenticated routes.
- ❌ NAV006: Error/fallback navigation – Failed; no fallback screen for deleted/null shared attachments, app crashes.
- ✅⚠️ NAV007: Automatic login for saved session – Passed with minor fix; redirects to profile screen instead of forums.

[**NOTES**](./mobile/notes/sept-21-2025.md)

- ❌ N001: Create a note manually – Failed; app crashes on creation. Minor keyboard overlay issue in editor.
- ✅ N002: View a note – Passed; remained functional, no regressions.
- ✅ N003: Edit/update a note – Passed; remained functional, no regressions.
- ✅ N004: Delete a note – Passed; remained functional, no regressions.
- ❌ N005: Change a note visibility – Failed; "private" notes still accessible by other users.
- ✅ N006: Generate a note summary from PDF – Passed; functional with refinements needed (rich text font).
- ✅ N007: Generate a note summary from Image – Passed; functional with refinements needed (rich text font).
- ✅ N008: Search a note – Passed; functional, no issues.

[**POMODORO**](./mobile/pomodoro/sept-21-2025.md)

- ✅ PT001: Customize time intervals – Passed; fixes from last test applied (buggy customization now resolved).
- ✅ PT002: Enabling/disabling Pomodoro drawer display – Passed; remained functional, no regressions.
- ✅ PT003: Full timer display – Passed; remained functional, no regressions.
- ✅ PT004: Timer operation – Passed; fixes from last test applied (unstable count/tick in bottomsheet view now resolved).

[**PROFILE**](./mobile/profile/sept-21-2025.md)

- ✅ PF001: View own profile – Passed; functional but refinements needed for viewing user’s posts (suggested UI improvements).
- ❌ PF002: View other user's profile – Failed; app crashes/force closes when attempting to view another user’s profile.

[**QUIZZES**](./mobile/quizzes/sept-21-2025.md)

- ✅⚠️ Q001: Create a quiz manually – Passed with minor issue (keyboard overlay hides bottom part; options for time duration and randomize quiz will be removed).
- ✅ Q002: Answer a quiz – Stable (no regression).
- ✅ Q003: Review a quiz – Stable (no regression).
- ✅ Q004: View all user attempts history – Passed (newly implemented this test).
- ✅ Q005: Answer a shared quiz in forums – Stable (no regression).
- ✅ Q006: View leaderboard rank of a shared quiz – Stable (no regression).
- ✅ Q007: Edit/update a quiz – Stable (no regression).
- ✅ Q008: Delete a quiz – Stable (no regression).
- ❌ Q009: Change a quiz visibility – Failed (private quizzes remain accessible to other users).
- ✅ Q010: Generate a quiz from note – Stable (no regression).
- ✅ Q011: Generate a quiz from PDF – Stable (no regression).
- ✅ Q012: Search a quiz – Passed (functional).

[**SETTINGS**](./mobile/settings/sept-21-2025.md)

- ⚠️ ST001: Change theme – Functional, but issue detected with system dark/light mode toggle (disappears after multiple switches).
- ✅ ST002: Change email address – Passed; functional but needs to enforce change limits.
- ✅ ST003: Verify email address – Passed; still functional
- ✅ ST004: Change name – Passed; functional but needs to enforce change limits.
- ✅ ST005: Change profile visibility – Passed; still functional
- ✅ ST006: Reset password – Passed; functional (web only, no mobile screen).

---

## MOBILE TESTS IN TABULAR FORMAT

| Module         | Test ID | Status | Summary                                                                                        |
| -------------- | ------- | ------ | ---------------------------------------------------------------------------------------------- |
| **AUTH**       | A001    | ✅     | Login functional; password peek suggested for better UX                                        |
|                | A002    | ✅     | Signup functional; password peek suggested for better UX                                       |
|                | A003    | ✅     | Logout remains functional                                                                      |
|                | A004    | ✅⚠️   | Forgot Password functional; mobile deprecated, to be web only                                  |
| **FLASHCARDS** | FL001   | ✅⚠️   | Create flashcard set manually; fixes implemented but issue remains when no flashcards exist    |
|                | FL002   | ✅     | View flashcard set functional; no regressions                                                  |
|                | FL003   | ❌     | Edit/update flashcard set fails; can only add cards, editing/deleting not supported            |
|                | FL004   | ✅     | Delete flashcard set remains functional; no regressions                                        |
|                | FL005   | ❌     | Change flashcard set visibility fails; private sets still accessible                           |
|                | FL006   | ✅     | Generate from note functional; preview issue fixed                                             |
|                | FL007   | ✅     | Generate from PDF functional; preview issue fixed                                              |
|                | FL008   | ✅     | Search flashcard set functional                                                                |
| **FORUMS**     | FO001   | ✅     | Read/view forum posts functional; no regressions                                               |
|                | FO002   | ✅     | Search posts functional; no regressions                                                        |
|                | FO003   | ✅     | Create a post functional; no regressions                                                       |
|                | FO004   | ✅     | Post attachments functional; UI refinements for selection indicator                            |
|                | FO005   | ✅     | Edit/update post functional; rich text now works properly                                      |
|                | FO006   | ✅⚠️   | Delete post functional; refinements suggested (move button, add confirmation pop-up)           |
|                | FO007   | ✅     | Upvote/downvote post functional; issue on full post voting fixed                               |
|                | FO008   | ✅⚠️   | Comment functional; refinements suggested (apply QuickEase Gabarito font)                      |
|                | FO009   | ✅     | Threaded replies functional; comment input field visible                                       |
|                | FO010   | ✅     | Upvote/downvote comment functional; no regressions                                             |
|                | FO011   | ✅     | Edit comment functional; no regressions                                                        |
|                | FO012   | ⚠️     | Notifications partially passed; threaded replies notifs broken, resolved report notifs missing |
|                | FO013   | 🚧     | Report a post/comment not yet implemented                                                      |
| **NAVIGATION** | NAV001  | ❌     | Navigation after login fails; back button returns to login instead of exiting app              |
|                | NAV002  | ❌     | Drawer navigation fails; buggy when accessing shared attachments                               |
|                | NAV003  | ✅     | Topside tab navigation functional; no regressions                                              |
|                | NAV004  | 🚧     | Deep linking not yet implemented; only available on web                                        |
|                | NAV005  | ✅     | Logout navigation functional; prevents return to auth routes                                   |
|                | NAV006  | ❌     | Error/fallback navigation fails; no fallback for deleted/null shared items, app crashes        |
|                | NAV007  | ✅⚠️   | Automatic login functional; minor fix needed (redirects to profile instead of forums)          |
| **NOTES**      | N001    | ❌     | Create note manually fails; app crashes, keyboard overlay issue in editor                      |
|                | N002    | ✅     | View note functional; no regressions                                                           |
|                | N003    | ✅     | Edit/update note functional; no regressions                                                    |
|                | N004    | ✅     | Delete note functional; no regressions                                                         |
|                | N005    | ❌     | Change note visibility fails; private notes still accessible                                   |
|                | N006    | ✅⚠️   | Generate summary from PDF functional; refinements needed (rich text font)                      |
|                | N007    | ✅⚠️   | Generate summary from Image functional; refinements needed (rich text font)                    |
|                | N008    | ✅     | Search note functional; no issues                                                              |
| **POMODORO**   | PT001   | ✅     | Customize time intervals functional; buggy customization fixed                                 |
|                | PT002   | ✅     | Drawer display toggle functional; no regressions                                               |
|                | PT003   | ✅     | Full timer display functional; no regressions                                                  |
|                | PT004   | ✅     | Timer operation functional; unstable bottomsheet tick fixed                                    |
| **PROFILE**    | PF001   | ✅     | View own profile functional; refinements suggested for viewing posts (UI improvements)         |
|                | PF002   | ❌     | View other user’s profile fails; app crashes/force closes                                      |
| **QUIZZES**    | Q001    | ✅⚠️   | Create quiz manually functional; minor issue (keyboard overlay, options deprecated)            |
|                | Q002    | ✅     | Answer quiz functional; no regressions                                                         |
|                | Q003    | ✅     | Review quiz functional; no regressions                                                         |
|                | Q004    | ✅     | View all user attempts history functional; newly implemented                                   |
|                | Q005    | ✅     | Answer shared quiz functional; no regressions                                                  |
|                | Q006    | ✅     | View leaderboard functional; no regressions                                                    |
|                | Q007    | ✅     | Edit/update quiz functional; no regressions                                                    |
|                | Q008    | ✅     | Delete quiz functional; no regressions                                                         |
|                | Q009    | ❌     | Change quiz visibility fails; private quizzes still accessible                                 |
|                | Q010    | ✅     | Generate quiz from note functional; no regressions                                             |
|                | Q011    | ✅     | Generate quiz from PDF functional; no regressions                                              |
|                | Q012    | ✅     | Search quiz functional; no issues                                                              |
| **SETTINGS**   | ST001   | ⚠️     | Change theme functional; bug with system dark/light mode toggle disappearing                   |
|                | ST002   | ✅     | Change email functional; limit enforcement needed                                              |
|                | ST003   | ✅     | Verify email address functional                                                                |
|                | ST004   | ✅     | Change name functional; limit enforcement needed                                               |
|                | ST005   | ✅     | Change profile visibility functional                                                           |
|                | ST006   | ✅     | Reset password functional (web only; no mobile screen)                                         |
