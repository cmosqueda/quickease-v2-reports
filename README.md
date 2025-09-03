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

## CONSOLIDATED LATEST REPORTS (AS OF SEPTEMBER 3, 2025)

_All contents in this section are the consolidated TLDRs from each test categories. This will be updated for every test iterations_

### MOBILE

[**AUTH**](./mobile/auth/sept-3-2025.md)

- ✅ Login and Signup modules are functional. Minor UX suggestion: Add password peek toggle for better usability.
- ✅ Logout works as expected via the logout button.
- ✅ Reset password takes user to the web version via email service.
- 🚧 Forgot password not yet implemented.

[**FLASHCARDS**](./mobile/flashcards/sept-3-2025.md)

- ✅ Manual creation, viewing, and editing of flashcard sets are fully functional.
- 📌 Flashcards display well with clear sequencing and interactivity.
- 🚧 Delete functionality, change visbility, and generate from notes are not yet implemented.
- 📄 Generating flashcards from PDF is functional and efficient (under 30 seconds)

[**FORUMS**](./mobile/forums/sept-3-2025.md)

- ✅ Core features like reading, searching, creating posts, attaching study materials, commenting, and voting on posts/comments are functional.
- ⚠️ Notifications are fetched in real time but need UI refinement (e.g., alert indicator on bell icon).
- 🚧 Editing and deleting posts/comments, as well as threaded replies, are not yet implemented.

[**NOTES**](./mobile/notes/sept-3-2025.md)

- ✅ Creating, viewing, and editing notes are functional with minor UI/UX suggestions:

  - Improve text indentation consistency
  - Apply custom font styling
  - Add toggle for bottom toolgroup in editor

- 🚧 Delete note and change visibility features are not yet implemented.
- ❌ Failed: Generate note summary from PDF or image (upload works, but content not generated and rendered)

[**POMODORO**](./mobile/pomodoro/sept-3-2025.md)

- ✅ Pomodoro drawer toggle works as expected.
- ❌ Customizing time intervals and accessing full timer display both fail due to a rendering issue (`Invalid RGBA format` error). Navigation and editing are blocked.
- 🛠️ Root cause appears to be a UI rendering bug affecting multiple modules. Needs urgent fix to restore full Pomodoro functionality.

[**QUIZZES**](./mobile/quizzes/sept-3-2025.md)

- ✅ Leaderboard viewing and quiz editing are functional. Editing works well but lacks options for time duration and randomization (available in web version).
- ⚠️ Manual quiz creation is partially working; missing key configuration options.
- ❌ Answering quizzes (both saved and shared) fails due to submission errors—toast popup appears, no data saved.
- 🚧 Review, history, delete, change visibility, and generate from note features are not yet implemented.
- 📃 Generating quiz from PDF is functional and efficient (under 30 seconds)

[**SETTINGS**](./mobile/settings/sept-3-2025.md)

- ✅ All core settings features passed:

  - Theme switching works smoothly.
  - Email and name changes are functional.
  - Email verification integrates with web interface.
  - Profile visibility toggle and profile viewing operate as expected.

- ⚠️ Minor limitations:
  - No restriction yet on how often users can change email or name.
  - Unverified accounts currently have full access—role-based restrictions not yet applied.
