# Example of integrating WebDataRocks with the Django framework

This repository contains a sample project that shows how to integrate [WebDataRocks](https://www.webdatarocks.com/) with the [Django framework](https://www.djangoproject.com/).

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
This will create database tables for the default Django apps. [Learn about the migrate command](https://docs.djangoproject.com/en/5.0/ref/django-admin/#migrate).

3. Run the sample project:
    - On Windows:
    ```bash
    py manage.py migrate
    ```
    - On macOS or Ubuntu/Linux:
    ```bash
    python3 manage.py runserver
    ```
You can access the project at `http://localhost:8000/`.

## Related docs
For details on how to integrate WebDataRocks into existing Django projects, check out the [integration with Django](https://www.webdatarocks.com/doc/integration-with-django/).

## Support
Feel free to ask WebDataRocks-related questions on [StackOverflow](https://stackoverflow.com/questions/tagged/webdatarocks).
