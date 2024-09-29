
# CRUD_FORM
This Windows Forms application provides basic functionalities to manage a simple user profile. It allows users to Insert, Delete, Update, and Search profile data, and displays the user details in a list view on the right side.

## Components
Input Fields
- Name: A text box for entering the user’s name.
- Country: A dropdown (combo box) to select a country.
- Gender: Radio buttons to select the user’s gender (Male or Female).
- Hobby: Checkboxes for selecting hobbies, such as Reading and - Painting.
- Status: A group box with radio buttons to select the user’s marital status (Married or Unmarried).
Buttons
- Insert: Inserts a new user profile with the data entered in the form fields.
- Delete: Deletes the selected user profile from the list.
- Update: Updates the selected profile based on the data entered in the form fields.
- Search: Searches the list of profiles based on the entered search criteria.
- View: Displays all the profiles currently stored.
Output Section
- The large box on the right side is a ListView or DataGridView, where user profile data is displayed in tabular format after it is inserted, searched, or updated
## Functionality
1. Insert:

- When the Insert button is clicked, the form collects data from the input fields and inserts a new record in the backend (or displays it in the view).
- The user profile includes details like Name, Country, Gender, Hobbies, and Marital Status.
2. Delete:

- Clicking Delete will remove the selected record from the backend and remove it from the view.
3. Update:

- The Update button updates the details of the selected profile in the list view based on the current values entered in the form fields.
4. Search:

- When Search is clicked, it will search for user profiles matching the search criteria (likely by name or country) and display the relevant profiles.
5. View:

- Clicking View will load all the stored profiles and display them in the list view.
## How to Use
1. Run the application.
2. Enter user details (Name, Country, Gender, Hobbies, Status).
3. Use the buttons to insert, update, delete, or search profiles.
4. The data will be displayed in the output section on the right.