# FormikForm
Creation of a React app using the Formik library to create a simple form with error/validation messages and a successful login popup if all fields are correctly filled.
# Download the .zip file and unzip it. In your terminal, in the unziped folder, type npm install. After that, type npm start. 
# Form specification : 
  The form contains :
    - Email field
    - Password field
    - Submit button
  The form has the following input validation rules:
    - If the username or password inputs are empty, display the message "Field required" under the text input.
    - If the username is not in an email format, display the message "Username should be an email" under the text input.
    - If the username and password pass the above validations, then display the message "Login Successful" in an alert box.
  The form has the following specific details:
    - The email input field should have the ID emailField
    - The email error message should be within a div element that has the ID emailError
    - The password input field should have the ID pswField
    - The password error message should be within a div element that has an ID pswError
    - The submit button should have an ID submitBtn
# Starter file source : MIT - FullStack Development with MERN (December 2022 cohort)
