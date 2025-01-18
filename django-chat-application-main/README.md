# Django Chat Application
A web-based chat application built using Django that enables users to communicate in real-time.

## Features
User authentication system (login/register/logout).
Real-time chat functionality (WebSocket/REST-based).
Multiple chat rooms for organized communication.
Responsive user interface.
Lightweight and scalable backend.
Installation
Follow these steps to set up the project locally:

## Prerequisites
Python 3.8+
Django 4.0+

## OUTPUT
![result](https://github.com/user-attachments/assets/df766706-8b7e-4628-917f-4b8017bc72fd)

Virtual environment tools (optional but recommended)
Steps

## Clone the Repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
Set Up a Virtual Environment (optional)


python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install Dependencies
pip install -r requirements.txt
Apply Migrations


python manage.py makemigrations
python manage.py migrate
Run the Development Server
python manage.py runserver
Access the Application Open your browser and navigate to http://127.0.0.1:8000/.

## Folder Structure
php
Copy
Edit
project/
├── chat/               # Django app for chat functionality
│   ├── migrations/     # Database migrations
│   ├── static/         # Static files (CSS, JS, images)
│   ├── templates/      # HTML templates
│   ├── views.py        # Application views
│   ├── urls.py         # App-specific URL configurations
├── project/            # Main project folder
│   ├── settings.py     # Project settings
│   ├── urls.py         # Main URL configurations
├── db.sqlite3          # SQLite database
├── manage.py           # Django management tool
├── requirements.txt    # Python dependencies


Tech Stack
Backend: Django
Frontend: HTML, CSS, JavaScript (optionally include Bootstrap)
Database: SQLite (default, can be switched to PostgreSQL/MySQL)
Real-time Communication: WebSocket or Django Channels (if applicable)

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions, feel free to reach out:

Name: Varadraj Kharosekar
GitHub: varadraj6055
Email: varadraj.k2002@gmail.com
