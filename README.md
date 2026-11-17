# Blood Donor Registration System

## Project Description
This is a simple Blood Donor Registration System developed using HTML, CSS, and JavaScript. The project allows users to register as blood donors by providing their personal information and blood group.

It includes form validation to make sure users enter correct information before registration. After successful registration, donor information is displayed dynamically in a table.

## Features

- **Donor Registration:** Users can enter their name, AIUB ID, mobile number, age, blood group, and other required information.
- **Form Validation:** Checks whether all required fields contain valid information.
- **AIUB ID Validation:** Uses Regular Expressions (RegEx) to check the AIUB ID format.
- **Mobile Validation:** Ensures the mobile number contains exactly 11 digits.
- **Age Validation:** Only accepts ages between 18 and 60.
- **Blood Group Selection:** Users can select their blood group from a dropdown menu.
- **Password Validation:** Checks the minimum password length and confirms both passwords match.
- **Donor List:** Displays registered donors in a dynamic HTML table.
- **Remove Donor:** Allows users to remove a registered donor from the table.
- **Donor Counter:** Automatically updates the total number of registered donors.
- **Reset Option:** Clears the form fields.

## Technologies Used

- **HTML:** Used to create the registration form and donor table.
- **CSS:** Used to design and style the webpage.
- **JavaScript:** Used for form validation, DOM manipulation, and dynamic table operations.

## JavaScript Concepts Used

- Variables (`let`)
- Arrays and Objects
- Functions
- If-Else Conditions
- Regular Expressions (RegEx)
- DOM Manipulation
- `getElementById()`
- `querySelector()`
- `createElement()`
- `appendChild()`
- `addEventListener()`
- `innerHTML`
- `push()`, `splice()`, and `indexOf()`

## How It Works

1. The user fills in the donor registration form.
2. JavaScript checks each field using validation conditions.
3. If any information is invalid, an error message is displayed.
4. If all information is valid, the donor is added to the donors array.
5. The donor's name, AIUB ID, and blood group are displayed in the table.
6. The total donor count is updated automatically.
7. Users can remove a donor using the Remove button.

## How to Run

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in any web browser.
4. Fill in the registration form and click **Register Donor**.

## Note

This is an academic practice project. Donor information is stored temporarily in a JavaScript array. Data will be lost when the webpage is refreshed because no database or backend is connected.
