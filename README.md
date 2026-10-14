# Django Product Store

## Setup
```bash
python -m venv venv && source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations products
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

## Use
1. Open http://127.0.0.1:8000/admin/, log in, and add products under **Products**.
2. Visit http://127.0.0.1:8000/products
3. The terminal running `runserver` prints all products stored in the database.
