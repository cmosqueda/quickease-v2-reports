# GUIDE FOR DOCUMENTING TEST REPORTS

**Options for creating structured reports:**

- Through google docs, or
- Through markdown files (provide link of your own github repository where you hosted it)

**If Markdown Files:**

For strict standards, I recommend creating folders first for each functionality for categorization. Then, inside those folders, create a markdown file, and give it a meaningful name. I suggest naming these markdown files as the date of when you wrote the test.

For example:

```
root-folder/ 		             => the top-level folder directory
   |— login/ 		             => should only contain all reports related to Login feature
   |     |— august-1-2025.md     => all test reports for LOGIN feature tested on August 1, 2025
   |     |— august-2-2025.md     => all test reports for LOGIN feature tested on August 2, 2025
   |
   |— register/ 			     => should only contain all reports related to Register feature
   |     |— august-1-2025.md     => all test reports for REGISTER feature tested on August 1
   |     |— august-2-2025.md     => all test reports for REGISTER feature tested on August 2

```

## Format for writing a report’s content (this format is the standard whether you opt to write reports on docs, or on markdown file)

- CODE NUMBER (insert a heading pls)
- DESCRIPTION
- STATUS - (pass or fail?)
- NETWORK TAB RESULTS (can be found at the inspect browser DOM)
- ERROR ENCOUNTERED (You can find hints on console logs or network tabs at inspect browser)
- FEEDBACK/SUGGESTIONS
