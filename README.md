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

## CONSOLIDATED LATEST REPORTS (AS OF AUGUST 6, 2025)

_All contents in this section are the consolidated TLDRs from each test categories. This will be updated for every test iterations_

[**ADMIN**](./admin/aug-6-2025.md)

- ✅ **All core features passed:** login, user search/view/edit, report viewing, email actions.

- ⚠️ **Minor issue:** Email delivery is delayed.

- ⚠️ **Failures/Not done:**

  - AD006: Delete user – Not implemented
  - AD010: Search reports – Not implemented
  - AD012: Delete user via report – Failed (404)

- 💡 **Suggestions:** Add severity rating + resolve button for reports, log resolved reports for future moderation.

[**AUTH**](./auth/aug-6-2025.md)

- Forgot password flow (L007) works.
- Password reset email sends successfully.

[**FLASHCARDS**](./flashcards/aug-6-2025.md)

- Keyboard controls now implemented

[**FORUMS**](./forums/aug-6-2025.md)

- Notifications modal (NF001) works.
- Mark as read (NF002) works, but updates only after page refresh.

[**NOTES**](./notes/aug-6-2025.md)

- Study option buttons (LN005) are now functional. Generating quiz and flashcards from notes works and can be successfully saved via clicking study options.

[**PROFILE**](./profile/aug-6-2025.md)

- Profile info displays, but some fields are still empty — Partially Passed
- Badge system works, but redundant "first post" badge pop-ups — Passed with minor issue
