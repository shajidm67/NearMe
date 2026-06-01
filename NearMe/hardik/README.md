# NearMe

A Django web application project located in this repository.

## Structure

- `manage.py` - Django project management script
- `hardik/` - Django project package with settings, URL configuration, ASGI/WGI, and app initialization
- `myapp/` - Django application package with models, views, admin, and static files

## Setup

1. Create and activate a Python virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

2. Install dependencies (add your project requirements here):
   ```bash
   pip install django
   ```

3. Apply migrations:
   ```bash
   python manage.py migrate
   ```

4. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Notes

- Static HTML files are stored in `myapp/static/`
- Update `hardik/settings.py` for database, static file settings, and installed apps as needed

## License

Add your license information here.
