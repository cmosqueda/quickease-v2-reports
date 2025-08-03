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

## CONSOLIDATED LATEST REPORTS (AS OF AUGUST 3, 2025)

_All contents in this section are the consolidated TLDRs from each test categories. This will be updated for every test iterations_

[**AUTH**](./auth/aug-3-2025.md)

- ✅ Login, Register, and Logout functionalities work properly with fast, responsive UI and no errors.
- ✅ Error-handling (via toasts/popups) is user-friendly and clearly communicates issues.
- ✅ Navigation between login/register screens is seamless.
- ✅ Security checks (e.g., valid credentials, no duplicate emails) are correctly enforced.
- ✅ Client-side validation ensures all required fields are completed before proceeding.
- ⚠️ Forgot Password functionality is not yet implemented.
- 📶 Network responses for login, register, and logout confirm fast and successful operations.

[**FLASHCARDS**](./flashcards/aug-3-2025.md)

- ✅ Users can manually create, view, edit, and delete flashcard sets successfully.
- ✅ Flashcard previews (front and back) display accurate data and render properly.
- ✅ Card flip animation works smoothly and enhances user experience.
- ✅ Editing works for both manually created and AI-generated flashcards.
- ✅ Ellipsis menu (for delete and visibility toggle) functions correctly.
- ✅ Navigation (e.g., back to Flashcards module) is seamless.
- ✅ Visibility toggling works with proper backend response.
- ⚠️ Flashcard sharing feature is not yet implemented.

[**FORUMS**](./forums/aug-3-2025.md)

- ✅ Users can create, edit, and delete posts successfully.
- ✅ Users can attach notes and flashcards to posts. (Quiz attachment pending visibility feature.)
- ✅ Voting (upvote/downvote) on posts and comments works as expected.
- ✅ Commenting and threaded replies function properly.
- ✅ Users can report posts and comments — however, users can currently report their own comments, which should be restricted.
- ✅ Search and filter features (by newest, top votes, comments) work smoothly.
- ⚠️ Categorization by tags is not yet implemented, but partially handled via search.

[**GENERATIVE-AI**](./generative-ai/aug-3-2025.md)

- ✅ Note Generation from Document works with minor delay; suggestion: add a loading indicator and success toast.
- ⚠️ Note Generation from Image is not yet implemented.
- ✅ Flashcard Generation from Notes & Documents works properly; some delay noted but acceptable.
- ✅ Quiz Generation from Notes & Documents works accurately; generation is slightly faster than other AI processes.
- ⚠️ General Suggestion: Add visual feedback (e.g., loading screen or toast) during and after generation for better user experience.

[**LIBRARY**](./library/aug-3-2025.md)

- ✅ Search functionality returns accurate results.
- ✅ Learner materials (notes, flashcards, quizzes) are fetched and displayed correctly.
- ✅ Filtering between AI-generated and user-created materials works as expected.
- ✅ No errors encountered in any of the tests.

[**NOTES**](./notes/aug-3-2025.md)

- ✅ Users can create, edit, view, and delete notes successfully.
- ✅ All markdown editor features work as expected.
- ✅ Notes save and load correctly, with both manual and AI-generated types supported.
- ✅ Functional buttons and navigation (e.g., back to Library) respond smoothly.
- ✅ Toggling note visibility is working and responsive.
- ✅ All actions show correct API responses with fast load times.
- ⚠️ Note sharing feature is not yet implemented.

[**POMODORO**](./pomodoro/aug-3-2025.md)

- ✅ Can customize timers
- ✅ Can enable or disable pomodoro popup display
- ✅ Can toggle persistent screen display

[**QUIZ**](./quiz/aug-3-2025.md)

- ✅ UI and buttons respond quickly (within 0.8s).
- ✅ Users can manually create, edit, and delete quizzes successfully.
- ✅ Quizzes can be answered and submitted with results saved accurately.
- ✅ Score calculation and quiz review (with correct answers, score, timestamp) function correctly.
- ✅ Navigation (e.g., back to Library) works seamlessly.
- ✅ Ellipsis icon renders properly and its delete option functions as expected.
- ✅ Editing also works for AI-generated quizzes.
- ⚠️ Sharing and quiz visibility/privacy features are not yet implemented.

[**SETTINGS**](./settings/aug-3-2025.md)

- ✅ Users can successfully change theme, email, name, and password.
- ✅ All settings updates function properly with no errors.
- ✅ Theme changes render correctly; account detail changes reflect as expected.
