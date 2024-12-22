# KundenApp
Purpose:

The application is designed to manage customer information, including first name, last name, email, and phone number, by saving it into a PostgreSQL database.
Graphical User Interface (GUI):

Built using Qt Designer, the GUI provides an intuitive and user-friendly experience.
Input fields for the following customer details:
Last name
First name
Email address
Phone number
A checkbox to indicate whether email notifications should be enabled.
A button to register the customer and save their details in the database.
Input Validation:

Email Validation:
Ensures that the email follows a standard format using a regular expression.
Displays an error message if the email is invalid.
Phone Number Validation:
Ensures the phone number is numeric and contains between 8 and 11 digits.
Rejects invalid phone numbers with a user-friendly error message.
Mandatory Fields:
Last name, first name, and phone number are required fields. The application prevents submission without these details.
Database Integration:

Uses PostgreSQL to store customer data securely.
The application connects to a database (clientsdb) and inserts customer records into a table named clients.
Data stored includes:
Last name
First name
Email (optional, based on checkbox selection)
Phone number
Handles database errors gracefully, displaying error messages in case of connection or query issues.
Feedback to the User:

On successful registration, a confirmation message displays the details of the newly added customer.
Errors are shown through message boxes for easy debugging and user guidance.
Error Handling:

Handles potential issues, such as database connection failures or invalid SQL queries, without crashing the application.
Provides clear feedback to users through QMessageBox dialogs.
