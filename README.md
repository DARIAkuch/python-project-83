# Page Analyzer
****
### Hexlet tests and linter status:
[![Actions Status](https://github.com/DARIAkuch/python-project-83/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/DARIAkuch/python-project-83/actions)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=DARIAkuch_python-project-83&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=DARIAkuch_python-project-83)

****

### Description
Page Analyzer is an online tool that assesses Websites on their SEO applicability, compared to how PageSpeed Insights works. 

****

### Required:


| Tool                                                                             | Description                                                                                                                                                                                                                                                                 |
|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [uv](https://docs.astral.sh/uv/)                                                 | "is an extremely fast Python package manager written in Rust. It is designed as a replacement for pip and pip-tools. It can also replace venv and pyenv."                                                                                                                   |            |
| [ruff](https://docs.astral.sh/ruff/)                                             | "Your Tool For Linter and Style Guide Enforcement"                                                                                                                                                                                                                          |
| [Flask](https://flask.palletsprojects.com/en/stable/)                            | "Flask is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications"                                                                                                        |
| [Gunicorn](https://docs.gunicorn.org/en/latest/index.html)                       | "Gunicorn ‘Green Unicorn’ is a Python WSGI HTTP Server for UNIX. It’s a pre-fork worker model ported from Ruby’s Unicorn project. The Gunicorn server is broadly compatible with various web frameworks, simply implemented, light on server resources, and fairly speedy." |
| [python-dotenv](https://pypi.org/project/python-dotenv/)                         | "Python-dotenv reads key-value pairs from a .env file and can set them as environment variables. It helps in the development of applications following the 12-factor principles."                                                                                           |
| [Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/)     | "Bootstrap is a powerful, feature-packed frontend toolkit. Build anything—from prototype to production—in minutes."                                                                                                                                                         |
| [Psycopg](https://getbootstrap.com/docs/5.3/getting-started/introduction/)       | "Psycopg – PostgreSQL database adapter for Python"                                                                                                                                                                                                                          |
| [validators](https://validators.readthedocs.io/en/latest/#module-validators.url) | "Python Data Validation for Humans™."                                                                                                                                                                                                                                       |
| [Requests](https://requests.readthedocs.io/en/latest/)                           | "Requests is an elegant and simple HTTP library for Python, built for human beings."                                                                                                                                                                                        |
| [Beautifulsoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)          | "Beautiful Soup is a Python library for pulling data out of HTML and XML files."                                                                                                                                                                                            |
---

## Installation
### Clone repository:
```
gh repo clone DARIAkuch/python-project-50
```
```
cd python-project-83
```
### For proper usage configure an .env file:
After cloning the repository, rename .env.example to .env and modify SECRET_KEY and DATABASE_URL variables.

****
### Install dependencies and generate a database with a command below:
```
make build
```
### Start the app with:

```
make start
```