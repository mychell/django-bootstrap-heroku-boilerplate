# django-bootstrap-heroku boilerplate

This is a boilerplate template to kickstart your django/bootstrap template with all the requirements to deploy to heroku in seconds

## Usage

Start a new project using this template:

```
django-admin.py startproject --template=https://github.com/mychell/django-bootstrap-heroku-boilerplate/archive/master.zip --extension=py,gitignore project_name

```

Install requirements via pip:

```
pip install -r requirements.txt
```

Run database migrations:

```
python manage.py migrate
```

Test Locally:

```
python manage.py runserver
```



## Before deploying to heroku

```
replace project_name in Procfile with actual projectname

```
```
-  Now you can run:  $ git add .

```





## Links


- Took a bunch of ideas and examples from this project: https://github.com/jcalazan/django-project-template/