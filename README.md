## Algorithmic music generation

This is the project for SWE599 class.

### Installation

MuseApp is developed using Python 3.10 and Django4 on Windows 10. The following guide is meant for Windows 10

for installation, the host system must have the following installed:

- Python3.10
- pip
- pipenv (also added to the environment variables)

1. Clone the project from the main branch and go to the project directory.

2. Start the virtual env

```virtualenv museapp```
```venv\Scripts\activate```

3. Add the Django secret key to the .env file under /museapp folder.

4. Install the dependencies

```python manage.py server```