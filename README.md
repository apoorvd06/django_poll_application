# Django Poll Application

A simple poll application built using Django by following the official Django tutorial.

## Features

- View the latest poll questions
- Vote on a poll
- View poll results
- Admin panel to add, edit, and delete polls

## Technologies Used

- Python
- Django
- HTML
- SQLite

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd django_poll_application
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   ```

   **Windows**
   ```bash
   venv\Scripts\activate
   ```

   **Linux/macOS**
   ```bash
   source venv/bin/activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

6. Open your browser and visit:
   ```
   http://127.0.0.1:8000/polls/
   ```

## Admin Panel

Create a superuser:

```bash
python manage.py createsuperuser
```

Then log in at:

```
http://127.0.0.1:8000/admin/
```

## Project Structure

```
django_poll_application/
├── manage.py
├── mysite/
├── polls/
├── db.sqlite3
├── requirements.txt
└── README.md
```

## License

This project is for learning purposes.
