CONTINUE FROM HERE :

This is a good time to test how the login and logout functionality works. Since there is still no user registration, the only way to add a user to the database is to do it via the Python shell, so run flask shell and enter the following commands to register a user:





WIPE DATABASE:
flask db downgrade base
flask db upgrade