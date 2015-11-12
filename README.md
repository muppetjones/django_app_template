# django_app_template
An app template for Django 1.7

To use:

```
./manage.py startapp --template=https://github.com/muppetjones/django_app_template/archive/master.zip myapp app_path
```

Where `app` is your app name, and `app_path` is where you want it, e.g., `apps/myapp`.

Then, make sure you change the directory names in three places:
* `static/css/app_name`
* `static/js/app_name`
* `templates/app_name`
