This master catalog lists all test cases for `QUIZZES -> Qxxx` module.

---

- **Q001: Create a quiz manually**

  - Description: The user should be able to create a new quiz through manual input.
  - Steps to perform:
    1. Navigate to the quiz screen via library.
    2. Click on the manually create button.
    3. Perform CRUD operations on the quiz's contents.
    4. Save the new quiz by clicking the save button.

- **Q002: Answer a quiz**

  - Description: The user should be able to answer an existing saved/created quiz.
  - Steps to perform:
    1. Open any of the existing quiz.
    2. Click on the start button.
    3. Attempt to answer the quiz.
    4. After answering, submit the attempt by clicking the submit button.

- **Q003: Review a quiz**

  - Description: The user should be able to review the saved answers, along with the corresponding correct answers of an answered quiz.
  - Steps to perform:
    1. Make sure that a quiz attempt has been recorded or saved.
    2. Click on a recorded attempt.

- **Q004: View all user attempts history**

  - Description: The user should be able to view a quiz's history which records the date the quiz was answered and its corresponding score.
  - Steps to perform:
    1. On an existing quiz, make sure that you have already made answer attempts.
    2. Head over to the your attempts tab to view quiz attempt's history

- **Q005: Answer a shared quiz in forums**

  - Description: The user should be able to answer a shared quiz in forums.
  - Steps to perform:
    1. On a post, look for a shared quiz attachment.
    2. Click on the shared quiz.
    3. Answer the shared quiz.
    4. Submit attempt by clicking submit button.

- **Q006: View leaderboard rank of a shared quiz**

  - Description: The user should be able to view the leaderboard rank of users who answered a shared quiz in forums.
  - Steps to perform:
    1. On a post, look for a shared quiz attachment.
    2. Click on the shared quiz.
    3. Head over to the shared quiz's leaderboard tab.

- **Q007: Edit/update a quiz**

  - Description: The user should be able to edit/update an existing quiz data.
  - Steps to perform:
    1. Open any of the existing quiz.
    2. Click on the edit button.
    3. Edit any contents inside the quiz by performing CRUD operations.
    4. Save the updated contents by clicking the save button.

- **Q008: Delete a quiz**

  - Description: The user should be able to delete an existing quiz data.
  - Steps to perform:
    1. Click on the kebab menu.
    2. Select the delete option.

- **Q009: Change quiz visibility**

  - Description: The user should be able to change visibility of existing quiz data.
  - Steps to perform:
    1. Click on the kebab menu.
    2. Click on the set to public/private option.

- **Q010: Search a quiz**
  - Description: The user should be able to search for an existing quiz.
  - Steps to perform:
    1. On the quiz tab, click on the search bar
    2. Enter the title of the quiz you wish to search.

---

## In tabular format:

| FEAT_CODE | Feature Name                    | Description                                                                                                                |
| --------- | ------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| Q001      | Create a quiz manually          | The user should be able to create a new quiz through manual input.                                                         |
| Q002      | Answer a quiz                   | The user should be able to answer an existing saved/created quiz.                                                          |
| Q003      | Review a quiz                   | The user should be able to review the saved answers, along with the corresponding correct answers of an answered quiz.     |
| Q004      | View a quiz's history           | The user should be able to view a quiz's history which records the date the quiz was answered and its corresponding score. |
| Q005      | Answer a shared quiz in forums  | The user should be able to answer a shared quiz in forums.                                                                 |
| Q006      | View leaderboard rank of a quiz | The user should be able to view the leaderboard rank of users who answered a shared quiz in forums.                        |
| Q007      | Edit/update a quiz              | The user should be able to edit/update an existing quiz data.                                                              |
| Q008      | Delete a quiz                   | The user should be able to delete an existing quiz data.                                                                   |
| Q009      | Change quiz visibility          | The user should be able to change visibility of existing quiz data.                                                        |
| Q010      | Search a quiz                   | The user should be able to search for an existing quiz.                                                                    |
