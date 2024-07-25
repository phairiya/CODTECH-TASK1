Name:PRISHA HAIRIYA

Company: CODTECH IT SOLUTIONS

ID: CT12DS1866

Domain: Web Developement

Duration: July to September 2024

Mentor: Neela Santhosh Kumar

OVERVIEW OF THE PROJECT

This To-Do app provides functionality to add, mark as completed, delete, and persist to-do items across sessions using local storage. It also includes a theme toggle feature for light and dark modes. The application is built using HTML, CSS, and JavaScript.

HTML Structure
The index.html file defines the layout and structure of the app. It includes:
A header section with a logo, theme toggle button, and a link to the GitHub repository.
A form for inputting new to-do items.
A section to display the list of to-do items.
CSS Styling
The style.css file defines the visual appearance of the app. Key points include:
Two main themes: lightmode and darkmode, with corresponding CSS variables for colors.
Styling for various components such as the header, form, and to-do items.
Animations for adding and deleting to-do items and transitioning between themes.
JavaScript Functionality
The app.js file contains the core logic for the app. Key functions and features include:
SVG Icons for Theme Toggle:

moonSVG and sunSVG define the SVGs for the moon and sun icons used in the theme toggle.
Todo List Management:

saveTodo(todoList): Saves the to-do list to local storage.
getTodo(): Retrieves the to-do list from local storage.
Form Submission:

formSubit(e): Handles the form submission event to add a new to-do item to the list. It creates a new to-do item, updates the DOM, and saves the updated list to local storage.
Todo Item Actions:

done(e): Marks a to-do item as completed or uncompleted. Updates the DOM and local storage accordingly.
deleteTodo(e): Deletes a to-do item from the list. Updates the DOM and local storage accordingly.
Theme Toggle:

changeTheme(): Toggles between light and dark modes. Updates the DOM and saves the current theme to local storage.
Initialization:

init(): Initializes the app by setting up event listeners, applying the saved theme, and loading the initial to-do list from local storage.
HTML Structure (index.html)
The document starts with a basic HTML5 structure.
The head section includes meta tags, the title, CSS links, and a script tag to include app.js.
The body contains:
A header with logo, theme toggle button, and GitHub link.
An input form for adding new to-do items.
A section to display the to-do items.
A footer with a bug report link and a hint for clicking the logo.
Usage
Add a To-Do Item:

Type a to-do item in the input field and press enter or click the submit button.
The item will appear in the to-do list.
Mark as Completed:

Click the checkmark button on a to-do item to mark it as completed.
Completed items are styled with a strikethrough and reduced opacity.
Delete a To-Do Item:

Click the delete button on a to-do item to remove it from the list.
Toggle Theme:

Click the sun/moon icon to switch between light and dark modes.
Key Features


Local Storage: Ensures that the to-do list and theme preferences are saved across sessions.
Responsive Design: The layout adjusts for different screen sizes.
Animations: Smooth transitions for adding, completing, and deleting to-do items, as well as for theme changes.

![to do](https://github.com/user-attachments/assets/b331b707-2952-4356-87ca-e60a8d8ab0cc)


