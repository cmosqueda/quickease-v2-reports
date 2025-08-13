# GUIDE FOR DOCUMENTING TEST REPORTS

**Options for creating structured reports:**

- Through google docs, or
- Through markdown files (provide link of your own github repository where you hosted it)

**If Markdown Files:**

For strict standards, I recommend creating folders first for each functionality for categorization. Then, inside those folders, create a markdown file, and give it a meaningful name. I suggest naming these markdown files as the date of when you wrote the test.

For example:

```
root-folder/ 		             => the top-level folder directory
   |— auth/ 		             => should only contain all reports related to Auth feature
   |     |— august-1-2025.md     => all test reports for AUTH feature tested on August 1, 2025
   |     |— august-2-2025.md     => all test reports for AUTH feature tested on August 2, 2025
   |
   |— flashcards/ 			     => should only contain all reports related to Flashcards feature
   |     |— august-1-2025.md     => all test reports for FLASHCARD feature tested on August 1
   |     |— august-2-2025.md     => all test reports for FLASHCARD feature tested on August 2

```

## Format for writing a report’s content (this format is the standard whether you opt to write reports on docs, or on markdown file)

- CODE NUMBER (insert a heading pls)
- DESCRIPTION
- STATUS - (pass or fail?)
- NETWORK TAB RESULTS (can be found at the inspect browser DOM)
- ERROR ENCOUNTERED (You can find hints on console logs or network tabs at inspect browser)
- FEEDBACK/SUGGESTIONS

## BLANK TEMPLATE

````
# CODE:

- **DESCRIPTION:**
- **STATUS:**
- **ERROR ENCOUNTERED:**
- **FEEDBACK/SUGGESTIONS:**

<!-- if necessary -->
- **NETWORK TAB RESULTS:**
  - **ACTION PERFORMED:**
  - **RESULTS:**
  ```
  name:
  status:
  type:
  response:
  size:
  time:
  ```


````

## OTHER TESTER'S REPO

- [**Sherri Tilan**](https://github.com/Tsherii/quickease_2.0-reports)
- [**Jalanie Baraocor**](https://github.com/jiyuutheosum/quickease_2.0-reports)

## CONSOLIDATED LATEST REPORTS (AS OF AUGUST 13, 2025)

_All contents in this section are the consolidated TLDRs from each test categories. This will be updated for every test iterations_

[**ADMIN**](./admin/aug-13-2025.md)

- **AD006** – Manage Users: Admin can now delete a user’s account from user management with confirmation modal; tested successfully.
- **AD009** – Report Search: Search function for reported posts/comments works as intended; results displayed correctly.
- **AD010** – Delete Reported Content: Admin can delete reported posts/comments; status updates to “Resolved – Deleted.”
- **AD011** – Delete User via Report Management: Admin can delete a user account from report management if necessary; status updates to “Resolved.”

[**EMAIL SERVICE**](./email-service/aug-13-2025.md)

- **ES004** – Request Email Change Verification: Initially failed (401 error) when clicking "verify email" button due to authentication requirement.
- **ES004 Update**: Verification succeeded when the account was logged in prior to requesting verification; process works as intended in that case.

### TILAN'S REPORT

**SETTINGS**

- ✅ LS006 (Profile Visibility Setting): Works as intended

## CONSOLIDATED LATEST REPORTS (AS OF AUGUST 12, 2025)

_All contents in this section are the consolidated TLDRs from each test categories. This will be updated for every test iterations_

[**ADMIN**](./admin/aug-12-2025.md)

- `AD006` – (MANAGE USERS) Delete user from Other Options: Not yet implemented
- `AD009` – (REPORT MANAGEMENT) Search specific report: Not yet implemented
- `AD010` – (REPORT MANAGEMENT) Delete reported post/comment: Passed, shows “Resolved - Deleted” status
- `AD011` – (REPORT MANAGEMENT) Delete user via reports: Failed (404 backend route missing), recommend adding confirmation modal for caution.

---

### TILAN'S REPORT

**FORUMS**

- ✅ LF021 (Forum Infinite Scroll): Infinite scroll works smoothly; posts load correctly when scrolling.
- ✅ Profile Viewing (PR001): Works correctly,
  - ✋ Minor UX suggestion: add a back button when viewing other profiles.
- ⭕ Not yet Implemented:
  - Reports: Viewing reports for posts (FR001) and comments (FR002).
  - Profile: Badge viewing (PR002).
- ✋ Suggestions on Post Creation:
  - Back button behavior, it should return to forum overview instead of remaining on the post page.
  - Add a confirmation button after selecting attachments to ensure user confidence.

**GENERATIVE-AI RELATED FEATURES**

- ✋ UX suggestion:
  - A toast notification in saving the generated notes.

**FLASHCARDS**

- ✅ Suggested keyboard controls for LF004 are implemented and working as expected.
- ⭕ Unimplemented Feature:
  - Flashcard set sharing via “more options” is not yet available.

**QUIZZES**

- ✅ Most quiz features are already implemented and working smoothly.
- ✅ Core Functionality (LQ004): Users can answer and review saved quizzes without issues.
- ⭕ Unimplemented Features:
  - Quiz sharing via "more options" is not yet implemented.
    Editing quiz visibility/privacy is also pending.
- ✋ UX Suggestion:
  - Use shaded circles for single-answer questions and visual indicators for answered and unanswered items to improve clarity and user experience.

**SUMMARY NOTES**

- ✅ Functional buttons are working perfectly
- ⚠️ However, UX flow improvement is recommended — after saving a generated quiz, redirecting users to the Quizzes section would enhance usability.
- ⭕ Unimplemented Feature
  - Note sharing via “More Options” (LN009) is still not implemented.
