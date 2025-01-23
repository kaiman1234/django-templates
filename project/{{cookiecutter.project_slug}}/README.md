# {{ cookiecutter.project_name }}

{{ cookiecutter.description }}

## File structure

The source of the Django project is under ``src``.

## Packages

### Django apps and packages

- ``environs[django]``
{%- if cookiecutter.use_django_extensions %}
- ``django-extensions`` [Github](https://github.com/django-extensions/django-extensions) [Docs](https://django-extensions.readthedocs.io/en/latest/)
{%- endif %}
