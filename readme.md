CONTINUE FROM HERE :

The @before_request decorator from Flask register the decorated function to be executed right before the view function. This is extremely useful because now I can insert code that I want to execute before any view function in the application, and I can have it in a single place. The implementation simply checks if the current_user is logged in, and in that case sets the last_seen field to the current time. I mentioned this before, a server application needs to work in consistent time units, and the standard practice is to use the UTC time zone. Using the local time of the system is not a good idea, because then what goes in the database is dependent on your location.



WIPE DATABASE:
flask db downgrade base
flask db upgrade





<hr>

## To run locally (windows):
1. git clone git@github.com:Lewish1998/microblog.git
2. cd microblog
3. python -m venv venv
4. .\venv\Scripts\activate
5. pip install -r requirements.txt
6. flask run