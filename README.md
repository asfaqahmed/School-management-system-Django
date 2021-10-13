# Django-School-Management-System

This app is meant to be used by school manager to manage their school records:


## Usage
It's best to install Python projects in a Virtual Environment. Once you have set up a VE, clone this project

```bash
git clone https://github.com/adigunsherif/Django-School-Management-System.git
```
Then

```bash
cd Django-School-Management-System
```
Run

```python
pip install -r requirements.txt #install required packages
python manage.py migrate # run first migration
python manage.py runserver # run the server
```
Then locate http://172.0.0.1:8000

## Admin Login
When you run migrate, a superuser is created.
```bash
username: admin
password: admin123
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


## Test
```base
python manage.py test
```

