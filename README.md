User Registration and Validation Form
-------------------------------------
This is a simple, client-side user registration form built using HTML, CSS, and pure JavaScript for validation. It demonstrates key principles of front-end form handling, providing immediate feedback to the user without needing to submit the form to a server.

Features:
---------
⦿ Required Fields: Enforces that Name, Email, Password, and Confirm Password fields are completed.
⦿ Password Match Validation: Checks that the Password and Confirm Password fields contain identical values.
⦿ Inline Error Messages: Provides user-friendly feedback by displaying red error messages directly below the input fields, instead of
using intrusive browser alert() pop-ups.
⦿ Input Highlighting: Invalid input fields are highlighted with a distinct red border for better visibility.
⦿ Client-Side Redirection: Upon successful validation, the user is redirected from the index.html (registration) page to a dashboard.html page (simulating a successful login).

Project Structure:
------------------
■ index.html: Contains the main registration form structure, including the input fields and dedicated <span> elements for displaying error messages.
■ style.css: Manages the visual presentation, including general form layout, button styles, and specific CSS rules for displaying red error text (.error-message) and highlighting invalid ■ inputs (.input-error-border).
■ script.js: Houses the core validation logic, including the validateForm() function that checks field emptiness and password matching, and controls the display of inline error messages.

How to Run
----------
➣ Clone or Download: Get the project files onto your local machine.
➣ Open index.html: Simply open the index.html file in any modern web browser.
➣ Test Validation: Try submitting the form with fields left blank or passwords that don't match to see the inline validation in action!
