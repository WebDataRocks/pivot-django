# Example of integrating WebDataRocks with the Django framework

[![WebDataRocks](https://cdn.webdatarocks.com/readmes/django.png)](https://www.webdatarocks.com/?r=rm_django)

This repository contains a sample project that shows how to integrate [WebDataRocks](https://www.webdatarocks.com/?r=rm_django) with the [Django framework](https://www.djangoproject.com/).

## Prerequisites

- [Python 3](https://www.python.org/downloads/)
- [Django](https://docs.djangoproject.com/en/4.2/intro/install/#install-django)

## Run the project

1. Download or clone this project from GitHub:
   ```bash
   git clone https://github.com/WebDataRocks/pivot-django.git
   cd pivot-django
   ```
2. Run the following command:

    - On Windows:
    ```bash
    py manage.py migrate
    ```
    - On macOS or Ubuntu/Linux:
    ```bash
    python3 manage.py migrate
    ```
   This will create database tables for the default Django apps. [Learn about the migrate command](https://docs.djangoproject.com/en/5.2/ref/django-admin/#migrate).

3. Run the sample project:

    - On Windows:
    ```bash
    py manage.py runserver
    ```
    - On macOS or Ubuntu/Linux:
    ```bash
    python3 manage.py runserver
    ```
You can access the project at `http://localhost:8000/`.

## Related docs

For details on how to integrate WebDataRocks into existing Django projects, check out the [integration with Django](https://www.webdatarocks.com/doc/js/integration-with-django/?r=rm_django).

## Support

For WebDataRocks-related questions, bug reports, and feature requests, please [create an issue on our GitHub](https://github.com/WebDataRocks/web-pivot-table/issues).
