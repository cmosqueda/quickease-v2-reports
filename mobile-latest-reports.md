# CONSOLIDATED LATEST REPORTS FOR MOBILE

_All contents in this section are the consolidated TLDRs from each test categories in mobile. This will be updated for every test iterations._

**Last Updated:** Sept. 13, 2025

---

## MOBILE TESTS IN LIST FORMAT

[**AUTH**](./mobile/auth/sept-13-2025.md)

- ✅ A001: Login – Functional; password peek option for password field suggested for better UX.
- ✅ A002: Signup – Functional; password peek option for password field suggested for better UX.
- ✅ A003: Reset Password – Functional; sends email service properly.
- ✅ A004: Logout – Functional, works as expected.
- ❌ A005: Forgot Password – Not implemented; no reset mechanism available on mobile.

[**FLASHCARDS**](./mobile/flashcards/sept-13-2025.md)

- 🚧 FL001: Create a flashcard set manually – Functional but confusing UX (long press vs tap); cannot fully edit or delete individual cards.
- ✅ FL002: View a flashcard set – Viewing works as expected, no issues.
- ❌ FL003: Edit/update a flashcard set – Failed, can only add cards; editing/deleting not supported.
- ✅ FL004: Delete a flashcard set – Passed, deletion works (accessed via long press).
- ✅ FL005: Change flashcard set visibility – Passed, visibility change is porperly functional.
- ⚠️ FL006: Generate a flashcard set from note – Passed with minor issues; card preview click triggers Call Stack error.
- ⚠️ FL007: Generate a flashcard set from PDF – Passed with minor issues; same Call Stack error as FL006.

[**FORUMS**](./mobile/forums/sept-13-2025.md)

- ✅ FO001: Read/view forum posts – Functional, no regressions.
- ✅ FO002: Search post on forums – Passed, new categories added (newest, top upvotes, most comments).
- ✅ FO003: Create a post – Passed, remained functional.
- ⚠️ FO004: Post attachments – Passed with minor UX issue (inconsistent selection indicator).
- ⚠️ FO005: Edit/update a post – Partially passed; edits apply but with delay.
- ✅ FO006: Delete a post – Passed, fully functional.
- ⚠️ FO007: Upvote/downvote a post – Partially passed; works in feed view but buggy in full post view.
- ✅ FO008: Comment on a post – Passed, remained functional.
- ⚠️ FO009: Threaded replies on comments – Passed with UX issue (comment field hidden by keyboard).
- ✅ FO010: Upvote/downvote a comment – Passed, no regressions.
- ✅ FO011: Edit a comment – Passed, remained functional.
- ⚠️ FO012: Notifications – Passed, but UI improvements suggested (add clearer titles/phrases).

[**NAVIGATION**](./mobile/navigation/sept-13-2025.md)

- ❌ NAV001: Navigation after login – Pressing the system back button after first-time login returns the user to the login screen instead of exiting the app. Exit should require double-press for better UX.
- ❌ NAV002: Drawer navigation – Navigation between modules retains states, but back navigation from a shared note in forums incorrectly redirects to the Notes screen.
- ✅ NAV003: Topside tab navigation – Switching between tabs (All, By Recent, AI-generated) works correctly without state loss.
- 🚧 NAV004: Deep linking – Not yet implemented in the app; currently only works in the web platform.
- ✅ NAV005: Logout navigation flow – Logging out redirects to the login screen and prevents back navigation to authenticated routes.
- ❌ NAV006: Error/fallback navigation – Deleted or null items (e.g., shared notes) trigger call stack errors instead of showing an error screen. Shared deletions should dynamically update in forum attachments.
- ✅ NAV007: Automatic login for saved session – Automatically logs in saved sessions but currently directs to the user profile screen; should redirect to the forums screen.

[**NOTES**](./mobile/notes/sept-13-2025.md)

- ✅ N001: Create a note manually – Works properly, refinements needed in rich text editor (fonts, indentation).
- ✅ N002: View a note – Functional, no issues found.
- ✅ N003: Edit/update a note – Functional, no issues found.
- ✅ N004: Delete a note – Now implemented, works properly.
- ✅ N005: Change a note visibility – Now implemented, works properly.
- ❌ N006: Generate a note summary from PDF – Upload works but content is not generated/rendered.
- ❌ N007: Generate a note summary from Image – Upload works but content is not generated/rendered.

[**POMODORO**](./mobile/pomodoro/sept-13-2025.md)

- ⚠️ PT001: Customize time intervals – Buggy. Save button doesn’t always apply changes.
- ✅ PT002: Drawer display toggle – Works properly, no issues.
- ✅ PT003: Full timer display – Works properly, no issues.
- ⚠️ PT004: Timer operates accurately – Works in drawer display but counts abnormally fast in bottomsheet display.

[**QUIZZES**](./mobile/quizzes/sept-13-2025.md)

- ⚠️ Q001: Create a quiz manually – Partially passed. Functional but missing options (time duration, randomize).
- ✅ Q002: Answer a quiz – Passed. Can now submit attempts.
- ✅ Q003: Review a quiz – Passed. Newly implemented, works properly.
- ❌ Q004: View a quiz's history – Not yet implemented.
- ✅ Q005: Answer a shared quiz in forums – Passed. Works properly.
- ✅ Q006: View leaderboard rank of a shared quiz – Passed. Remains functional.
- ❌ Q007: Edit/update a quiz – Failed. Edit button missing.
- ✅ Q008: Delete a quiz – Passed. Now implemented, works properly.
- ❌ Q009: Change quiz visibility – Failed. State change does not apply properly.
- ✅ Q010: Generate a quiz from note – Passed. Now implemented, works properly.
- ✅ Q011: Generate a quiz from PDF – Passed. Remains functional.

[**SETTINGS**](./mobile/settings/sept-13-2025.md)

- ✅ ST001: Change theme – Passed, remained functional
- ✅ ST002: Change email address – Passed, can change but limit enforcement needed
- ✅ ST003: Verify email address – Passed, remained functional
- ✅ ST004: Change name – Passed, can change but limit enforcement needed
- ✅ ST005: Change profile visibility – Passed, remained functional

## MOBILE TESTS IN TABULAR FORMAT

| Module         | Test ID | Status | Summary                                                                                       |
| -------------- | ------- | ------ | --------------------------------------------------------------------------------------------- |
| **AUTH**       | A001    | ✅     | Login functional; password peek suggested for better UX                                       |
|                | A002    | ✅     | Signup functional; password peek suggested for better UX                                      |
|                | A003    | ✅     | Reset Password functional; sends email properly                                               |
|                | A004    | ✅     | Logout functional                                                                             |
|                | A005    | ❌     | Forgot Password not implemented                                                               |
| **FLASHCARDS** | FL001   | 🚧     | Create flashcard set manually; UX confusing, cannot fully edit/delete cards                   |
|                | FL002   | ✅     | View flashcard set works as expected                                                          |
|                | FL003   | ❌     | Edit/update flashcard set; can only add cards, editing/deleting not supported                 |
|                | FL004   | ✅     | Delete flashcard set works (accessed via long press)                                          |
|                | FL005   | ✅     | Change flashcard set visibility functional                                                    |
|                | FL006   | ⚠️     | Generate from note; minor issues, card preview triggers Call Stack error                      |
|                | FL007   | ⚠️     | Generate from PDF; minor issues, same Call Stack error as FL006                               |
| **FORUMS**     | FO001   | ✅     | Read/view forum posts functional                                                              |
|                | FO002   | ✅     | Search posts; new categories added                                                            |
|                | FO003   | ✅     | Create a post functional                                                                      |
|                | FO004   | ⚠️     | Post attachments functional with minor UX issue                                               |
|                | FO005   | ⚠️     | Edit/update post partially passed; edits delayed                                              |
|                | FO006   | ✅     | Delete post functional                                                                        |
|                | FO007   | ⚠️     | Upvote/downvote post partially passed; buggy in full post view                                |
|                | FO008   | ✅     | Comment on post functional                                                                    |
|                | FO009   | ⚠️     | Threaded replies; comment field hidden by keyboard                                            |
|                | FO010   | ✅     | Upvote/downvote comment functional                                                            |
|                | FO011   | ✅     | Edit comment functional                                                                       |
|                | FO012   | ⚠️     | Notifications functional; UI improvements suggested                                           |
| **NAVIGATION** | NAV001  | ❌     | Back button after first-time login returns to login screen; should exit app with double press |
|                | NAV002  | ❌     | Drawer navigation; back navigation from shared note misdirects to Notes screen                |
|                | NAV003  | ✅     | Topside tab navigation works correctly without state loss                                     |
|                | NAV004  | 🚧     | Deep linking not yet implemented in app; only works on web                                    |
|                | NAV005  | ✅     | Logout navigation functional; prevents back navigation to auth routes                         |
|                | NAV006  | ❌     | Error/fallback navigation fails; deleted/null items trigger call stack errors                 |
|                | NAV007  | ✅     | Automatic login functional; redirects to profile screen instead of forums                     |
| **NOTES**      | N001    | ✅     | Create note manually functional; refinements in rich text editor needed                       |
|                | N002    | ✅     | View note functional                                                                          |
|                | N003    | ✅     | Edit/update note functional                                                                   |
|                | N004    | ✅     | Delete note functional                                                                        |
|                | N005    | ✅     | Change note visibility functional                                                             |
|                | N006    | ❌     | Generate summary from PDF fails; upload works but content not rendered                        |
|                | N007    | ❌     | Generate summary from Image fails; upload works but content not rendered                      |
| **POMODORO**   | PT001   | ⚠️     | Customize time intervals buggy; save button sometimes fails                                   |
|                | PT002   | ✅     | Drawer display toggle works properly                                                          |
|                | PT003   | ✅     | Full timer display works properly                                                             |
|                | PT004   | ⚠️     | Timer operates accurately in drawer; counts fast in bottomsheet                               |
| **QUIZZES**    | Q001    | ⚠️     | Create quiz manually; missing options (time, randomize)                                       |
|                | Q002    | ✅     | Answer quiz functional; can submit attempts                                                   |
|                | Q003    | ✅     | Review quiz functional; newly implemented                                                     |
|                | Q004    | ❌     | View quiz history not implemented                                                             |
|                | Q005    | ✅     | Answer shared quiz functional                                                                 |
|                | Q006    | ✅     | View leaderboard functional                                                                   |
|                | Q007    | ❌     | Edit/update quiz failed; edit button missing                                                  |
|                | Q008    | ✅     | Delete quiz functional                                                                        |
|                | Q009    | ❌     | Change quiz visibility fails; state change not applied                                        |
|                | Q010    | ✅     | Generate quiz from note functional                                                            |
|                | Q011    | ✅     | Generate quiz from PDF functional                                                             |
| **SETTINGS**   | ST001   | ✅     | Change theme functional                                                                       |
|                | ST002   | ✅     | Change email address functional; limit enforcement needed                                     |
|                | ST003   | ✅     | Verify email address functional                                                               |
|                | ST004   | ✅     | Change name functional; limit enforcement needed                                              |
|                | ST005   | ✅     | Change profile visibility functional                                                          |
