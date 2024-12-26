##  Form Validation
This project demonstrates how to create a user registration form in React using **React Hook Form** with basic validation for email and password fields.

### Features
- **Email Validation**: Ensures the entered email follows a valid format (e.g., user@example.com).
- **Password Validation**: Ensures the password is at least 6 characters long.
- **Real-time Error Messages**: Shows real-time validation errors if the user enters incorrect data.
  
### Installation

1. Clone the repository:

```
https://github.com/phattharaphorn/form-validation.git  
```

2. Install dependencies:

```
npm install
```

3. Run the app:

```
npm start
```

4. Open the browser at http://localhost:3000.
  
### How It Works
1. Email Field: The email input field uses a regular expression (regex) to check if the entered email is in a valid format.

2. Password Field: The password input requires at least 6 characters, and it will show an error message if the user tries to submit without meeting the minimum length requirement.

3. Real-Time Validation: Errors are displayed next to the form fields immediately after the user interacts with them.

