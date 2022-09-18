# Welcome to Microblog!

This is an example application featured in my [Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world). See the tutorial for instructions on how to work with it.

## Start command

Start the app in production like this:

```
flask db upgrade && flask translate compile && gunicorn microblog:app
```

Start the worker like this:

```
rq worker microblog-tasks
```
