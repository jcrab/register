# register
Create a simple PHP database application.  Secure database access with a login form.  Finally, allow new users to register and use your app.

Create the database functionality first.

- Create the database using the DDL provided.
- Modify index.php to select all data (except the id) from the primary table.
- Display the data using an HTML table (see w3schools.com).

Once you have tested your homepage, secure this page with a login form that uses the database table containing a hashed password.  Make sure that only users who have logged in can access the data.

Allow new user registration:

- Provide a new user form with support for a username and two passwords.
- Make sure the username is not already in the database.
- Make sure that the two passwords match.
- Insert a new row with the new credentials (test with plaintext first).
- Hash the password before insertion.

Test the final application.
