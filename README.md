# Social Book

**Social Book** is a Django web application that allows users to register, log in, upload books, and view other registered users. This project demonstrates basic Django functionality and integrates CSS styling, file uploads, and user authentication.

## Project Structure

social_book/
├── manage.py
├── social_book/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── users/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── forms.py
├── static/
│   └── css/
│       └── style.css
├── templates/
│   ├── base.html
│   ├── register.html
│   ├── login.html
│   ├── view_users.html
│   └── upload_books.html
├── .gitignore
└── requirements.txt


## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/TubaHussain2007/social_book.git
   cd social_book

2. **Create and Activate a Virtual Environment**


python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
Install Dependencies


pip install -r requirements.txt
Apply Migrations


python manage.py migrate
Create a Superuser (Optional)


python manage.py createsuperuser
Run the Development Server

python manage.py runserver

Access the application at http://127.0.0.1:8000/.

