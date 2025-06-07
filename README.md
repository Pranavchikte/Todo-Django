# Django Todo Application

A simple and efficient Todo application built with Django that helps you manage your tasks effectively.

## Features

- User authentication (login/logout)
- Create, read, update, and delete tasks
- Task management interface
- SQLite database for data storage
- Responsive design

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- Virtual environment (recommended)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Pranavchikte/Todo-Django.git
cd Todo
```

2. Create and activate a virtual environment:
```bash
# Windows
python -m venv .venv
.venv\Scripts\activate

# Linux/Mac
python3 -m venv .venv
source .venv/bin/activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Run database migrations:
```bash
python manage.py migrate
```

5. Create a superuser (admin):
```bash
python manage.py createsuperuser
```

6. Start the development server:
```bash
python manage.py runserver
```

The application will be available at `http://127.0.0.1:8000/`

## Project Structure

```
Todo/
├── Todo/                 # Main Todo application
├── Todo_Django/         # Django project settings
├── templates/           # HTML templates
├── db.sqlite3          # SQLite database
├── manage.py           # Django management script
└── requirements.txt    # Project dependencies
```

## Usage

1. Access the admin interface at `http://127.0.0.1:8000/admin/` using your superuser credentials
2. Navigate to the main application at `http://127.0.0.1:8000/`
3. Log in to your account
4. Start managing your tasks!

## Development

- The project uses Django 5.2.2
- SQLite is used as the database
- Templates are stored in the `templates/` directory
- Static files are managed through Django's static file handling

## Contributing

1. Fork the repository
2. Create a new branch for your feature
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 