CONTINUE FROM HERE :

The get_reset_password_token() function returns a JWT token as a string, which is generated directly by the jwt.encode() function.



WIPE DATABASE:
* flask db downgrade base
* flask db upgrade





<hr>

## To run locally (windows):
1. git clone git@github.com:Lewish1998/microblog.git
2. cd microblog
3. python -m venv venv
4. .\venv\Scripts\activate
5. pip install -r requirements.txt
6. flask run