CONTINUE FROM HERE :

Go ahead and try the pagination support. First make sure you have more than three blog posts written. This is easier to see in the explore page, which shows posts from all users. You are now going to see just the three most recent posts. If you want to see the next three, type http://localhost:5000/explore?page=2 in your browser's address bar.

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