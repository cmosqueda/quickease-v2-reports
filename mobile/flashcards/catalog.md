This master catalog lists all test cases for `FLASHCARDS -> FLxxx` module.

---

## In list format:

- **FL001: Create a flashcard set manually**

  - Description: The user should be able to create flashcard sets through manual input.
  - Steps to perform:
    1. Navigate to the flashcards screen.
    2. Click on the plus button.
    3. Select the create manually button.
    4. Perform CRUD operations on the flashcard set's front and back contents.
    5. Save the new flashcard set by clicking the save button.

- **FL002: View a flashcard set**

  - Description: The user should be able to view the contents of any existing flashcards.
  - Steps to perform:
    1. Open any of the existing flashcard sets.
    2. Interact with the cards by using keyboard controls (for web), clicking the next or previous buttons, or clicking the cards' foreground to flip the card's front-face or back-face.

- **FL003: Edit/update a flashcard set**

  - Description: The user should be able to edit any existing flashcard set's content.
  - Steps to perform:
    1. Open any of the existing flashcard sets.
    2. Click on the edit button.
    3. Edit any contents inside the flashcard set by performing CRUD operations.
    4. Save the updated contents by clicking the save button.

- **FL004: Delete a flashcard set**

  - Description: The user should be able to delete any existing flashcard set.
  - Steps to perform:
    1. Long press on any of the existing set. This should display the floating options.
    2. Click on the delete button.

- **FL005: Change a flashcard set visibility**

  - Description: The user should be able to change visibility of any existing flashcard set.
  - Steps to perform:
    1. Long press on any of the existing set. This should display the bottomsheet options.
    2. Click on the set to public/private button.

- **FL006: Generate a flashcard set from note**

  - Description: The user should be able to pick an existing note and generate a flashcard set from it.
  - Steps to perform:
    1. On the Flashcards screen, click on the plus button.
    2. Select the generate button. Clicking this should display the bottomsheet options.
    3. Select the **select from notes** option. Then, choose an existing note to generate a flashcard set.
    4. Perform CRUD operations or save the generated flashcard set.

- **FL007: Generate a flashcard set from PDF**

  - Description: The user should be able to pick a PDF and generate a flashcard set from it.
  - Steps to perform:
    1. On the Flashcards screen, click on the plus button.
    2. Select the generate button. Clicking this should display the bottomsheet options.
    3. Select the **upload file** option. Then, choose a locally owned file document to generate a flashcard set.
    4. Perform CRUD operations or save the generated flashcard set.

- **FL008: Search a flashcard set**

  - Description: The user should be able to search for an existing flashcard set.
  - Steps to perform:
    1. Click on the search button
    2. Enter the title of the flashcard set you wish to search.

---

## In tabular format:

| FEAT_CODE | Feature Name                       | Description                                                                 |
| --------- | ---------------------------------- | --------------------------------------------------------------------------- |
| FL001     | Create a flashcard set manually    | The user should be able to create flashcard sets through manual input.      |
| FL002     | View a flashcard set               | The user should be able to view the contents of any existing flashcards.    |
| FL003     | Edit/update a flashcard set        | The user should be able to edit any existing flashcard set's content.       |
| FL004     | Delete a flashcard set             | The user should be able to delete any existing flashcard set.               |
| FL005     | Change a flashcard set visibility  | The user should be able to change visibility of any existing flashcard set. |
| FL006     | Generate a flashcard set from note | The user should be able to pick an existing note and generate a set.        |
| FL007     | Generate a flashcard set from PDF  | The user should be able to pick a PDF and generate a flashcard set from it. |
| FL008     | Search a flashcard set             | The user should be able to search for an existing flashcard set.            |
