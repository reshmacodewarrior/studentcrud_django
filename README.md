
# Student Management System (Django CRUD)

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

A complete CRUD (Create, Read, Update, Delete) application for managing student records, built with Django and Bootstrap.


## Features

- **Student Management**
  - Add new students with all relevant details
  - View, edit, and delete existing records
  - Data validation for all fields
- **User Interface**
  - Responsive design with Bootstrap 5
  - Clean, intuitive dashboard
  - Confirmation dialogs for deletions
- **Admin Panel**
  - Full-featured Django admin interface
  - Export data to CSV/Excel

## Technologies Used

- **Backend**: Django 5.0
- **Frontend**: HTML5, Bootstrap 5
- **Database**: SQLite (Django ORM)
- **Authentication**: Django Admin

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/student-management-system.git
   cd student-management-system
   ```

2. **Set up virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create superuser (for admin access)**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run development server**
   ```bash
   python manage.py runserver
   ```

7. **Access the application**
   - Frontend: http://localhost:8000
   - Admin: http://localhost:8000/admin

## Project Structure

```
studentcrud/
├── student/                  # Main app
│   ├── migrations/           # Database migrations
│   ├── templates/            # HTML templates
│   ├── admin.py              # Admin configuration
│   ├── models.py             # Database models
│   ├── views.py              # Application logic
│   └── urls.py              # App URLs
├── studentcrud/              # Project config
├── db.sqlite3                # Database
└── manage.py                 # Django CLI
```



