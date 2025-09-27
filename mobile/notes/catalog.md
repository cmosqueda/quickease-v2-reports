This master catalog lists all test cases for `NOTES -> Nxxx` module.

---

## In list format:

- **N001: Create a note manually**

  - Description: The user should be able to create a new note through manual input.
  - Steps to perform:
    1. Navigate to the notes screen.
    2. Click on the plus button.
    3. Select the create manually button.
    4. Edit note's contents by manipulating the markdown rich text.
    5. Save the new note by clicking the save button.

- **N002: View a note**

  - Description: The user should be able to view any existing notes.
  - Steps to perform:
    1. Open any of the existing notes.
    2. View the note's contents.

- **N003: Edit/update a note**

  - Description: The user should be able to edit any existing note's content.
  - Steps to perform:
    1. Open any of the existing notes.
    2. Edit any contents inside the notes.
    3. Save the updated contents by clicking the save button.

- **N004: Delete a note**

  - Description: The user should be able to delete any existing note.
  - Steps to perform:
    1. Long press on any of the existing notes. This should display the floating options.
    2. Click on the delete button.

- **N005: Change a note visibility**

  - Description: The user should be able to change visibility of any existing note.
  - Steps to perform:
    1. Long press on any of the existing notes. This should display the bottomsheet options.
    2. Click on the set to public/private button.

- **N006: Generate a note summary from PDF**

  - Description: The user should be able to upload a PDF and generate a summary note from it.
  - Steps to perform:
    1. On the notes screen, click on the plus button.
    2. Select the generate button. Clicking this should display the bottomsheet options.
    3. Select the **upload file** option. Then, choose a locally owned file document to generate a note summary.
    4. Edit the note's content or save the generated note.

- **N007: Generate a note summary from Image**

  - Description: The user should be able to upload an image and generate a summary note from it.
  - Steps to perform:
    1. On the notes screen, click on the plus button.
    2. Select the generate button. Clicking this should display the bottomsheet options.
    3. Select the **upload image** option. Then, choose a locally owned file document to generate a note summary.
    4. Edit the note's content or save the generated note.

- **N008: Search a note**

  - Description: The user should be able to search for an existing note.
  - Steps to perform:
    1. Click on the search button
    2. Enter the title of the note you wish to search.

- **N009: Share a note via URL copy**
  - Description: The user should be able to share a public note to external apps/third party by sharing its URL.
  - Steps to perform:
    1. Long press on any of the existing note. This should display the floating options.
    2. Click on the share link.

---

## In tabular format:

| FEAT_CODE | Feature Name                       | Description                                                                                     |
| --------- | ---------------------------------- | ----------------------------------------------------------------------------------------------- |
| N001      | Create a note manually             | The user should be able to create a new note through manual input.                              |
| N002      | View a note                        | The user should be able to view any existing notes.                                             |
| N003      | Edit/update a note                 | The user should be able to edit any existing note's content.                                    |
| N004      | Delete a note                      | The user should be able to delete any existing note.                                            |
| N005      | Change a note visibility           | The user should be able to change visibility of any existing note.                              |
| N006      | Generate a note summary from PDF   | The user should be able to upload a PDF and generate a summary note from it.                    |
| N007      | Generate a note summary from Image | The user should be able to upload an image and generate a summary note from it.                 |
| N008      | Search a note                      | The user should be able to search for an existing note.                                         |
| N009      | Share a note via URL copy          | The user should be able to share a public note to external apps/third party by sharing its URL. |
