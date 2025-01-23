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
{%- if cookiecutter.use_django_model_utils %}
- ``django-model-utils``
  [Github](https://github.com/jazzband/django-model-utils)
  [Docs](https://django-model-utils.readthedocs.io/en/latest/)
{%- endif %}

## Settings

### Security

{%- if cookiecutter.use_secure_proxy %}
- Use HTTP header to determine secure connection (HTTPS)
{%- endif %}
