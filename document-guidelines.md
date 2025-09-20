# DOCUMENTATION GUIDELINES

This contains the guidelines to follow for documenting test reports.

---

**Options for creating structured reports:**

- Through google docs, or
- Through markdown files (provide link of your own github repository where you hosted it)

**If Markdown Files:**

## DIRECTORY GUIDE

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

## TESTING DOCUMENTATION GUIDELINES (Updated Sept. 13, 2025)

- All test case references are stored in `catalog.md` with unique IDs:
  - ADMINxxx -> Admin module (web only)
  - ESxxx -> Email services module (web only)
  - GENAIxxx -> AI generation features (web only)
  - Axxx -> Auth module
  - FLxxx -> Flashcards module
  - FOxxx -> Forums module
  - Nxxx -> Notes module
  - PTxxx -> Pomodoro Timer module
  - PFxxx -> Profile module
  - Qxxx -> Quizzes module
  - STxxx -> Settings module
  - NAVxxx -> System Navigations (New, for mobile only)
- Each catalog's feature logs follow this format:

```
**FEAT_CODE: Feature name**
  - Description: _brief description here_
  - Steps to perform:
    1.  step 1
    2.  step 2
    3.  step 3
```

- Test iterations remain on each file with its corresponding date (ex. `sept-3-2025.md`). However, it will now have this new format:

### For Web Frontend:

````
ALL TESTS FOR [Feature] ON [Date]

TLDR:
- 🚧 lorem ipsum dolor sit amet
- ✅ lorem ipsum dolor sit amet
- ❌ lorem ipsum dolor sit amet

---

# What was tested
- **FEAT_xx: [Feature name]**
  - Status: ✅ Passed / ❌ Failed / 🚧 Not implemented
  - Notes: [Any details, errors, or suggestions]
  - Network Tab Results (browser inspect):
      - Action performed: [Detailed steps and actions performed in testing the feature/module]
      - Request/Response Details
         ```
         name:
         status:
         type:
         response:
         size:
         time:
         ```

- **FEAT_xx: [Feature name]**
  - Status:
  - Notes:
  - Network Tab Results (browser inspect):
      - Action performed: [Detailed steps and actions performed in testing the feature/module]
      - Request/Response Details
         ```
         name:
         status:
         type:
         response:
         size:
         time:
         ```

---

# Comparison with last iteration ([Previous Date])
- **FEAT_xx** – [e.g., “Still passing, no regressions”]
- **FEAT_xx** – [e.g., “Now fixed, previously failed due to X”]
- **FEAT_xx** – [e.g., “Still failing, same issue persists”]
- **FEAT_xx** – [e.g., “Newly tested feature, no prior record”]

````

**Example:**

````
ALL TESTS FOR Flashcards Module ON Sept. 20, 2025

TLDR:
- ✅ Successfully created a new flashcard deck
- ❌ Editing a flashcard deck failed (API returned 500 error)
- 🚧 Delete functionality not yet implemented

---

# What was tested

- **FL001: Create Flashcard Deck**
  - Status: ✅ Passed
  - Notes: Deck was created successfully and appeared in the dashboard list.
  - Network Tab Results (browser inspect):
      - Action performed: Submitted "Create Deck" form with title **Biology 101** and 10 initial cards.
      - Request/Response Details:
         ```
         name: createDeck
         status: 200 OK
         type: fetch
         response: {"message":"Deck created successfully","deckId":"dck_12345"}
         size: 1.2 KB
         time: 340 ms
         ```

- **FL002: Edit Flashcard Deck**
  - Status: ❌ Failed
  - Notes: Attempted to edit "Biology 101" deck title to "Biology 101 - Updated". UI showed loading spinner but never updated; API returned error.
  - Network Tab Results (browser inspect):
      - Action performed: Edited deck title field → Clicked "Save Changes"
      - Request/Response Details:
         ```
         name: updateDeck
         status: 500 Internal Server Error
         type: fetch
         response: {"error":"Unexpected server error"}
         size: 850 B
         time: 620 ms
         ```

- **FL003: Delete Flashcard Deck**
  - Status: 🚧 Not implemented
  - Notes: Delete button is visible in UI but not wired to any functionality.
  - Network Tab Results (browser inspect):
      - Action performed: Clicked "Delete" on "Biology 101" deck
      - Request/Response Details:
         ```
         name: deleteDeck
         status: —
         type: —
         response: —
         size: —
         time: —
         ```

---

# Comparison with last iteration (Sept. 13, 2025)
- **FL001** – Still passing, no regressions
- **FL002** – Newly failing (previously passed on Sept. 13, 2025; API now returns 500 error)
- **FL003** – Still not implemented, same issue persists



````

### For Mobile Frontend:

```
ALL TESTS FOR [Feature] ON [Date]

TLDR:
- 🚧 lorem ipsum dolor sit amet
- ✅ lorem ipsum dolor sit amet
- ❌ lorem ipsum dolor sit amet

---

# What was tested
- **FEAT_xx: [Feature name]**
  - Status: ✅ Passed / ❌ Failed / 🚧 Not implemented
  - Notes: [Any details, errors, or suggestions]

- **FEAT_xx: [Feature name]**
  - Status:
  - Notes:

---

# Comparison with last iteration ([Previous Date])
- **FEAT_xx** – [e.g., “Still passing, no regressions”]
- **FEAT_xx** – [e.g., “Now fixed, previously failed due to X”]
- **FEAT_xx** – [e.g., “Still failing, same issue persists”]
- **FEAT_xx** – [e.g., “Newly tested feature, no prior record”]

```

**Example:**

```
ALL TESTS FOR Quizzes Module ON Sept. 20, 2025

TLDR:
- ✅ Quiz creation flow works as expected
- ❌ Timer countdown does not reset when starting a new quiz
- 🚧 Quiz sharing feature not yet implemented

---

# What was tested

- **Q001: Create a Quiz**
  - Status: ✅ Passed
  - Notes: User was able to create a quiz with 5 questions and save it. Quiz appeared correctly in the "My Quizzes" list.

- **Q002: Quiz Timer Reset**
  - Status: ❌ Failed
  - Notes: When starting a new quiz after completing one, the timer continues from the previous session instead of resetting to full duration.

- **Q003: Share Quiz**
  - Status: 🚧 Not implemented
  - Notes: Share button visible but no action performed when tapped.

---

# Comparison with last iteration (Sept. 13, 2025)
- **Q001** – Still passing, no regressions
- **Q002** – Newly failing (previously passed; issue introduced after recent update)
- **Q003** – Still not implemented, same issue persists


```

- This replaces the old “per-feature test file + consolidated notes” system. This reduces redundancy in re-documenting functional tests from previous test iterations.
- Documentations before this change are still valid, though. Only the format and rulesets were changed.
- **Update (Sept. 20, 2025):** Deprecated all tests in the `web/library` directory, which previously contained library screen tests. The reason for deprecation is that the screen tests in this directory are better categorized as loosely coupled component tests rather than representing the entire Library module’s functionality. Moving forward, tests related to this module will be specified within their respective modules:
  - flashcards/ -> FLxxx
  - quizzes/ -> Qxxx
  - notes/ -> Nxxx
