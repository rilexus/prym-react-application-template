##Sign Up Page
The following requirements MUST be implemented with React:
It MUST contain:
* Last name input field
* First name input field
* Nick name input field
* Email input field
* Password input field
* Repeat password input field
* "Show Address" checkbox
* All address related fields MUST only be visible if the "Show Address" checkbox is checked.
* Street input field
* House number input field
* ZIP input field
* City input field
* The redux store
* Text area field for additional information.
* A submit button

* All form values MUST be connected to a redux-store.
* All form values MUST be persistent after a page reload.
* You MUST NOT use any external libraries except redux related.
* The application SHOULD be extendable.

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
* You MUST not use external form validation libraries.
* Your implementation SHOULD contain test with a framework of your choice.

* You MAY implement design of some sort.
 

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL
NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and
"OPTIONAL" in this document are to be interpreted as described in
[RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).