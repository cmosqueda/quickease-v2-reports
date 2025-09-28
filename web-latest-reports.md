# CONSOLIDATED LATEST REPORTS FOR WEB

_All contents in this section are the consolidated TLDRs from each test categories in web. This will be updated for every test iterations._

**Last Updated:** Sept. 28, 2025

---

## WEB TESTS IN LIST FORMAT

### All tested and reviewed on SEPTEMBER 28, 2025

[**FORUMS**](./web/forums/sept-28-2025.md)

- ✅ FO001: Read/view forum posts – Passed; no regressions
- ✅ FO002: Search posts on forums – Passed; no regressions
- ❌ FO003: Create a post – Failed in mobile screen size; create post button is hidden.
- ✅ FO004: Post attachments – Passed; no regressions
- ✅ FO005: Edit/update a post – Passed; no regressions
- ✅ FO006: Delete a post – Passed; no regressions
- ✅ FO007: Upvote/downvote post – Passed; no regressions
- ✅ FO008: Comment on a post – Passed; no regressions
- ✅ FO009: Threaded replies on comments – Passed; no regressions
- ✅ FO010: Upvote/downvote comment – Passed; no regressions
- ✅ FO011: Edit a comment – Passed; no regressions
- 🚧 FO012: Notifications – Partially passed; Notifications for reports resolved by admin to user not yet implemented.
- ✅⚠️ FO013: Report a post/comment – Passed; reported comments not reflecting on ADMIN’s report management tab
- ✅ FO014: Share a forum post via URL copy – Passed; no regressions

[**FLASHCARDS**](./web/flashcards/sept-28-2025.md)

- ✅ FL001: Create a flashcard set manually – Passed; no regressions
- ⚠️ FL002: View a flashcard set – Passed with refinements needed; Flashcard Title too big on mobile responsive screen size
- ✅ FL003: Edit/update a flashcard set – Passed; no regressions
- ✅ FL004: Delete a flashcard set – Passed; no regressions
- ✅ FL005: Change a flashcard set visibility – Passed; no regressions
- ✅ FL006: Search a flashcard set – Passed; no regressions
- 🚧 FL007: Share a flashcard via URL copy – Not yet implemented

[**NOTES**](./web/notes/sept-28-2025.md)

- ✅ N001: Create a note manually – Passed; no regressions
- ✅ N002: View a note – Passed; no regressions
- ✅ N003: Edit/update a note – Passed; no regressions
- ✅ N004: Delete a note – Passed; no regressions
- ✅ N005: Change a note visibility – Passed; no regressions
- ✅ N006: Search a note – Passed; no regressions
- ✅ N007: Share a note via URL copy – Passed; copy-to-clipboard and sharing link functional

[**QUIZZES**](./web/quizzes/sept-28-2025.md)

- ✅ Q001: Create a quiz manually – Passed; no regressions
- ✅ Q002: Answer a quiz – Passed; no regressions
- ⚠️ Q003: Review a quiz – Passed with refinements needed; mobile UI issue with "donut percentage" overlapping container
- ✅ Q004: View all user attempts history – Passed; no regressions
- ✅ Q005: Answer a shared quiz in forums – Passed; no regressions
- ✅ Q006: View leaderboard rank of a shared quiz – Passed; no regressions
- ✅ Q007: Edit/update a quiz – Passed; no regressions
- ✅ Q008: Delete a quiz – Passed; no regressions
- ✅ Q009: Change quiz visibility – Passed; no regressions
- ✅ Q010: Search a quiz – Passed; no regressions
- 🚧 Q011: Share a quiz via URL copy – Not yet implemented

[**ADMIN tested SEPT 24**](https://github.com/Tsherii/quickease_2.0-reports/blob/main/admin/sept-24-25.md)

- ✅ ADMIN001 (Login): Works correctly; redirects to dashboard.
- ⭕ ADMIN002 (User Search): Not yet implemented.
  - ✅ Reviewed by Mosqueda, **ADMIN002 User search** is implemented already.
- ✅ ADMIN003 (View Account): User details display correctly.
- ✅ ADMIN004 (Update Account): Updates save and reflect.
- ✅ ADMIN005 (Delete Account): Accounts removed successfully.
- ✅ ADMIN006 (Password Reset Email): Reset link sent and received.
- ✅ ADMIN007 (Verification Email): Verification link sent and functional.
- 🚧 ADMIN008 (Delete Reported Content): Partially passed; only reported posts show on reports management, reported comments do not reflect.
- ✅ ADMIN009 (Delete Violator): Violator accounts removed successfully.
- ✅ ADMIN010 (Search Reports): Works correctly.

✋ **Suggestions**

- ADMIN001 (Login): Add sorting for user accounts by creation date in Manage User Dashboard.
- Reports Management Dashboard: Add sorting/filtering by date, unresolved reports shown first.
- ADMIN004 (Update Account): Notify users when admins change their account details.
- ADMIN008 (Delete Reported Content): Add a warning pop-up before permanent deletion.
- ADMIN010 (Search Reports): Add a back button to return to the dashboard.
- 🚧 Remove/disable admin settings

[**PROFILE tested SEPT 22**](https://github.com/Tsherii/quickease_2.0-reports/blob/main/profile/sept-20-25.md)

- 🚧 PF001: View own profile – Partially passed; profile and stats load correctly, UX suggestion: show stats tab before badges.
- ✅ PF002: View other's profile – functional, works properly;

---

## WEB TESTS IN TABULAR FORMAT

### All tested and reviewed on SEPTEMBER 28, 2025

| Module         | Test ID  | Status | Summary                                                                     |
| -------------- | -------- | ------ | --------------------------------------------------------------------------- |
| **FORUMS**     | FO001    | ✅     | Read/view forum posts – Passed; no regressions                              |
|                | FO002    | ✅     | Search posts on forums – Passed; no regressions                             |
|                | FO003    | ❌     | Create a post – Failed in mobile screen size; create post button hidden     |
|                | FO004    | ✅     | Post attachments – Passed; no regressions                                   |
|                | FO005    | ✅     | Edit/update a post – Passed; no regressions                                 |
|                | FO006    | ✅     | Delete a post – Passed; no regressions                                      |
|                | FO007    | ✅     | Upvote/downvote post – Passed; no regressions                               |
|                | FO008    | ✅     | Comment on a post – Passed; no regressions                                  |
|                | FO009    | ✅     | Threaded replies on comments – Passed; no regressions                       |
|                | FO010    | ✅     | Upvote/downvote comment – Passed; no regressions                            |
|                | FO011    | ✅     | Edit a comment – Passed; no regressions                                     |
|                | FO012    | 🚧     | Notifications – Partially passed; resolved reports to users not implemented |
|                | FO013    | ✅⚠️   | Report post/comment – Passed; comments not reflecting on ADMIN tab          |
|                | FO014    | ✅     | Share forum post via URL copy – Passed; no regressions                      |
| **FLASHCARDS** | FL001    | ✅     | Create flashcard set manually – Passed; no regressions                      |
|                | FL002    | ⚠️     | View flashcard set – Passed; Flashcard Title too big on mobile              |
|                | FL003    | ✅     | Edit/update a flashcard set – Passed; no regressions                        |
|                | FL004    | ✅     | Delete a flashcard set – Passed; no regressions                             |
|                | FL005    | ✅     | Change flashcard set visibility – Passed; no regressions                    |
|                | FL006    | ✅     | Search a flashcard set – Passed; no regressions                             |
|                | FL007    | 🚧     | Share flashcard via URL copy – Not yet implemented                          |
| **NOTES**      | N001     | ✅     | Create a note manually – Passed; no regressions                             |
|                | N002     | ✅     | View a note – Passed; no regressions                                        |
|                | N003     | ✅     | Edit/update a note – Passed; no regressions                                 |
|                | N004     | ✅     | Delete a note – Passed; no regressions                                      |
|                | N005     | ✅     | Change a note visibility – Passed; no regressions                           |
|                | N006     | ✅     | Search a note – Passed; no regressions                                      |
|                | N007     | ✅     | Share a note via URL copy – Passed; functional                              |
| **QUIZZES**    | Q001     | ✅     | Create a quiz manually – Passed; no regressions                             |
|                | Q002     | ✅     | Answer a quiz – Passed; no regressions                                      |
|                | Q003     | ⚠️     | Review a quiz – Passed; mobile UI issue with donut percentage display       |
|                | Q004     | ✅     | View user attempts history – Passed; no regressions                         |
|                | Q005     | ✅     | Answer shared quiz in forums – Passed; no regressions                       |
|                | Q006     | ✅     | View leaderboard rank – Passed; no regressions                              |
|                | Q007     | ✅     | Edit/update a quiz – Passed; no regressions                                 |
|                | Q008     | ✅     | Delete a quiz – Passed; no regressions                                      |
|                | Q009     | ✅     | Change quiz visibility – Passed; no regressions                             |
|                | Q010     | ✅     | Search a quiz – Passed; no regressions                                      |
|                | Q011     | 🚧     | Share a quiz via URL copy – Not yet implemented                             |
| **ADMIN**      | ADMIN001 | ✅     | Login – Works correctly; redirects to dashboard                             |
|                | ADMIN002 | ✅     | User search – Reviewed and confirmed to have been implemented               |
|                | ADMIN003 | ✅     | View account – Passed; details display correctly                            |
|                | ADMIN004 | ✅     | Update account – Passed; updates save and reflect                           |
|                | ADMIN005 | ✅     | Delete account – Passed; accounts removed successfully                      |
|                | ADMIN006 | ✅     | Password reset email – Passed; reset link functional                        |
|                | ADMIN007 | ✅     | Verification email – Passed; functional                                     |
|                | ADMIN008 | 🚧     | Delete reported content – Partially passed; reported comments missing       |
|                | ADMIN009 | ✅     | Delete violator – Passed; accounts removed successfully                     |
|                | ADMIN010 | ✅     | Search reports – Passed; functional                                         |
| **PROFILE**    | PF001    | 🚧     | View own profile – Partially passed; UX: show stats tab before badges       |
|                | PF002    | ✅     | View other's profile – Passed; functional                                   |
