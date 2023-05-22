# Form Validation

This project demonstrates a simple form validation implementation using HTML and JavaScript. It includes a login form that validates the input fields for the username and password.

## Getting Started

To get started with this project, follow the instructions below:

1. Clone the repository:

git clone https://github.com/infoajaykushwah/form-validatoin.git


2. Open the `index.html` file in a web browser.

## Form Validation

The form validation is performed using JavaScript. The following validations are implemented:

- User Name:
  - The username field should not be empty.
  - The username should have a minimum of 3 characters.

- Password:
  - The password field should not be empty.

If any of the validation conditions fail, appropriate error messages will be displayed next to the respective input fields.

The form submission will be prevented if any validation errors occur. Only when all fields pass validation, the form will be submitted.

## Code Explanation

The code uses JavaScript to handle the form validation. The validation logic is defined in the `validateForm` function, which is triggered when the form is submitted.

The `validateForm` function performs the following steps:

1. Retrieves the username and password input fields from the HTML document.
2. Sets an initial `flag` variable to `true`.
3. Validates the username field:
   - Checks if it is empty.
   - Checks if it has a minimum length of 3 characters.
   - Sets appropriate error messages and updates the `flag` variable accordingly.
4. Validates the password field:
   - Checks if it is empty.
   - Sets appropriate error messages and updates the `flag` variable accordingly.
5. Returns the `flag` variable. If it is `true`, the form will be submitted; otherwise, the submission will be prevented.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

