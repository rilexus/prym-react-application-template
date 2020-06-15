##Sign Up Page
The second page under the URL `/signup` MUST represent an sign up page.
It MUST contain:
* Some sort of navigation bar
* Last name input field
* First name input field
* Nick name input field
* Email input field
* Password input field
* Repeat password input field
* "Show Address" checkbox
* Street input field
* House number input field
* ZIP input field
* City input field
* Text area field for additional information
* All address related fields MUST only be visible if the "Show Address" checkbox is checked.
* A submit button

The form MUST submit the information only when the following requirements are met:
* Last name input field MUST be at least 2 characters long.
* First name input field MUST be at least 2 characters long.
* Password must be at least 6 characters long.
* Password must contain at least 2 numbers.
* Password and repeat password fields MUST contain the same value.
* Nick name input field MAY not be empty.
* Street input field MUST be at least 4 characters long.
* City input field MUST be at least 4 characters long.
* Text area MAY not be empty.
* Email input field MUST be a valid email.
* ZIP input field MUST be 5 characters long and all characters MUST be decimal numbers.
* All input fields which must contain a value MUST have a value.
* Submit button SHOULD be disabled when all the input requirements are not met.

You MUST not use external form validation libraries.