# django-calaccess-project-template

A custom template for initializing a new Django project with our CAL-ACCESS applications.

Uses the [built-in](https://docs.djangoproject.com/en/dev/ref/django-admin/#startproject-projectname-destination) Django ``startproject`` templating system.

Still experimental, so don't get your hopes up.

Getting started
---------------

Create a virtual enviroment to work inside.

```bash
$ virtualenv my-environment
```

Jump in and turn it on.

```bash
$ cd my-environment
$ . bin/activate
```

Install Django.

```bash
$ pip install django
```

Create a new Git repository.

```bash
$ git init repo
```

Download and install a project in there using this template.

```bash
$ django-admin.py startproject --extension=py,.gitignore --template=https://github.com/california-civic-data-coalition/django-calaccess-project-template/archive/master.zip project repo
```

Now that the template has landed, jump in and install the project's Python dependencies.

```bash
$ cd repo
$ pip install -r requirements.txt
```
