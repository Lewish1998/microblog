CONTINUE FROM HERE :

[Asynchronous Emails](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xiii-i18n-and-l10n)

There is an even harder case to handle. Some string literals are assigned outside a web request, usually when the application is starting up, so at the time these texts are evaluated there is no way to know what language to use. An example of this are the labels associated with form fields.



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