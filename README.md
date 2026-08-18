# Yatube API

REST API for Yatube, a social networking platform where users can publish posts, leave comments, follow other users, and interact with content.

## Tech Stack

- Python 3.7
- Django
- Django REST Framework
- SQLite
- pytest

## Features

- User authentication
- Create, edit, and delete posts
- Comments
- User subscriptions
- REST API endpoints
- Permissions and access control

## Running the Project

Clone the repository:

```bash
git clone https://github.com/snake8555/api_final_yatube.git
cd api_final_yatube
```

Create and activate a virtual environment:

```bash
python3 -m venv env
source env/bin/activate
```

Install dependencies:

```bash
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

Run migrations:

```bash
python3 manage.py migrate
```

Start the development server:

```bash
python3 manage.py runserver
```

## Author

Vladimir Zhurov
