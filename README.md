# Mark-Manson-Blogsite
I remake of mark manson's blog site
# Django Blogging App

The Django Blogging App is a minimalistic, full-stack blogging platform inspired by Mark Manson's clean and matured design style. It focuses on simplicity, readability, and the use of minimal JavaScript.

## Features

- User-friendly and clean design.
- Easily customizable for your blogging needs.
- Minimal use of JavaScript for improved performance.
- Responsive design for various screen sizes.

## Getting Started

These instructions will help you get your Django Blogging App up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

- Python 3.x
- Django
- pip3

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/django-blogging-app.git

cd [app file]

python -m venv venv
source venv/bin/activate  # On macOS and Linux
venv\Scripts\activate  # On Windows
pip install -r requirements.txt

python manage.py migrate

python manage.py createsuperuser


python manage.py runserver
