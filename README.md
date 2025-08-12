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

## CONSOLIDATED LATEST REPORTS (AS OF AUGUST 11, 2025)

_All contents in this section are the consolidated TLDRs from each test categories. This will be updated for every test iterations_

[**FORUMS**](./forums/aug-11-2025.md)

- PASSED: Viewing all posts and infinite scroll functions properly for feature **LF021**, but ther is a cutoff date limit for how many posts can be fetched by the state management.

[**PROFILE**](./profile/aug-11-2025.md)

- PARTIALLY PASSED: Previous issue with repetitive badge toast popup is now fixed. But there is an issue that potentially lies inside the forums as the badge seems to be dependent with it, meaning, even though certain conditions are properly met, any of the badge only takes effect when the user posts something inside the forums. Please look into this.

- **UPDATE:** PASSED - Previously reported issue about badges being dependent to forums now fixed.

## CONSOLIDATED LATEST REPORTS (AS OF AUGUST 12, 2025)

_All contents in this section are the consolidated TLDRs from each test categories. This will be updated for every test iterations_

[**ADMIN**](./admin/aug-12-2025.md)

- `AD006` – Delete user from Other Options: Not yet implemented
- `AD009` – Search specific report: Not yet implemented
- `AD010` – Delete reported post/comment: Passed, shows “Resolved - Deleted” status
- `AD011` – Delete user via reports: Failed (404 backend route missing), recommend adding confirmation modal for caution
