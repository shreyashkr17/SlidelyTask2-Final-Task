# Form1.vb
This file (`Form1.vb`) contains the main form of the application.

## Overview
Form1 serves as the entry point and main user interface for interacting with submission management functionalities.

## Key Features
- **Keyboard Shortcuts**: Allows users to quickly access functionalities using keyboard shortcuts (`Ctrl+V` for viewing submissions and `Ctrl+N` for creating submissions).
- **Submission Management**: Provides options to view, create, and search submissions.
- **Integration**: Integrates with other forms (`ViewSubmissionForm`, `CreateSubmissionForm`, `SearchResultForm`) to handle specific tasks.

## Usage
Ensure that all necessary dependencies are installed and the application is connected to the appropriate backend service (`http://localhost:3000` in this example).

## Notes
- This form is designed to provide a seamless user experience for managing submissions.
- Error handling is implemented to manage exceptions during form operations.

## Image:
![Final Task 1](https://github.com/shreyashkr17/SlidelyTask2-Final-Task/assets/97216718/8ff741e7-2264-49a7-a81b-5a8ef9980e54)

# ViewSubmissionForm.vb
This file (`ViewSubmissionForm.vb`) handles the display and navigation of submissions.
This file (`EditSubmissionForm.vb`) allows users to edit existing submissions.
This file (`SearchResultForm.vb`) displays search results based on email criteria.

## Overview
  1. ViewSubmissionForm displays submission details retrieved from a backend service and allows navigation through submissions.
  2. EditSubmissionForm enables users to modify submission details retrieved from a backend service and save the changes.
  3. SearchResultForm retrieves submission details matching a specified email address from a backend service and displays them.

## Key Features
### For ViewSubmissionForm.vb
- **Navigation**: Users can navigate through submissions using "Next" and "Previous" buttons.
- **Interaction**: Provides options to edit, delete, and view submission details.
- **Error Handling**: Includes error messages for failed operations and network issues.
### For EditSubmissionForm.vb
- **Editing**: Allows users to update submission details such as name, email, phone number, GitHub link, and stopwatch time.
- **Validation**: Ensures all changes are correctly saved to the backend service.
- **Integration**: Integrates with the backend service (`http://localhost:3000/edit` in this example) to update submission data.
### For SearchResultForm.vb
- **Search**: Searches submissions based on email input.
- **Navigation**: Allows navigation through search results using "Next" and "Previous" buttons.
- **Error Handling**: Displays messages for unsuccessful searches or network issues.

## Usage
Ensure that the application is connected to the backend service (`http://localhost:3000` in this example) to fetch submission data.
Select a submission to edit, make necessary changes, and click "Update" to save the modifications.
Enter an email address to search for corresponding submission details from the backend service (`http://localhost:3000/read-by-email` in this example).

## Notes
### For ViewSubmissionForm.vb 
- Use caution when deleting or editing submissions to avoid unintended data loss.
- Handles both successful and unsuccessful retrieval of submission details gracefully.
### For EditSubmissionForm.vb
- Always ensure that all form fields are correctly filled out before submitting.
- Error messages will display in case of submission failures or network issues.
### For SearchResultForm.vb
- Handle with care to avoid unintended data modifications or loss.
- Error messages will display if there are issues with updating submission details.

## Image
![Final Task 3](https://github.com/shreyashkr17/SlidelyTask2-Final-Task/assets/97216718/f59baaa2-569d-40f0-89b5-adcddd2f312d)
![Final Task 5](https://github.com/shreyashkr17/SlidelyTask2-Final-Task/assets/97216718/9e18f8aa-0f75-4fcd-afef-871b2fd46b3e)
![Final Task 4](https://github.com/shreyashkr17/SlidelyTask2-Final-Task/assets/97216718/31271825-78eb-4a7e-8cb5-19941083cab0)


# CreateSubmissionForm.vb
This file (`CreateSubmissionForm.vb`) allows users to create new submissions.

## Overview
CreateSubmissionForm provides a user interface for entering submission details and submitting them to a backend service.

## Key Features
- **Stopwatch**: Tracks time spent on form entries using a stopwatch.
- **Validation**: Ensures all required fields are filled before submission.
- **Keyboard Shortcuts**: Supports keyboard shortcuts (`Ctrl+T` to toggle stopwatch and `Ctrl+S` to submit the form).

## Usage
Fill out the submission form with appropriate details and click "Submit" to send the data to the backend service (`http://localhost:3000/submit` in this example).

## Notes
- Always ensure that all form fields are correctly filled out before submitting.
- Error messages will display in case of submission failures or network issues.

## Images
![Final Task 2](https://github.com/shreyashkr17/SlidelyTask2-Final-Task/assets/97216718/3b15ac69-e8fb-4fa3-aded-41ac3f960530)

