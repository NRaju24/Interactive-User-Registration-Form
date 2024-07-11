# Interactive-User-Registration-Form

Technologies Used
          HTML: To structure the form.
          CSS: For styling the form elements and layout.
          JavaScript: To handle form validation and interactivity.
          Bootstrap: To enhance UI components and ensure responsiveness.
          SheetDB: To submit and store form data in a Google Sheet.
Key Features
Form Structure:
Input Fields:
          Includes fields for first name, last name, email, phone number, password, and confirm password.
          Responsive Layout: Utilizes Bootstrap’s grid system for a flexible and responsive design.
        
Dynamic Validation:

Name Validation:
          Ensures names are alphabetic and meet length requirements.
          Provides real-time feedback on the number of characters needed.
Phone Number Validation:
          Checks for a valid 10-digit number starting with digits 6-9.
          Displays immediate validation messages.
Password Validation:
          Requires at least one uppercase letter, one lowercase letter, one number, one special character, and a minimum length of 9 characters.
          Real-time messages show which requirements are not met.
Password Match:
          Confirms that the password and confirm password fields match.
          Provides instant feedback on whether the passwords match.
Styling:

Custom Styles: CSS is used to style the form controls, buttons, and layout.
Bootstrap: Enhances overall styling and ensures responsiveness.
Visual Appeal: Background images and color adjustments improve the visual design.
Form Submission:

Data Storage: Upon successful validation, form data is submitted to a Google Sheet using the SheetDB API.
         Error Prevention: The form prevents submission if validation fails, ensuring that only valid data is submitted.
Error Messages:
          Provides real-time error messages for invalid inputs.
          Guides users to correct their inputs before form submission.


