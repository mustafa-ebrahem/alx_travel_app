# ALX Travel App

A comprehensive travel listing application built with Django that allows users to explore and book travel accommodations and experiences.

## 📋 Overview

ALX Travel App is a platform where travelers can discover accommodations, attractions, and experiences. Property owners can list their properties, and travelers can browse, search, and book their perfect travel experience.

## 🚀 Features

- User authentication and authorization
- Property and experience listings with detailed descriptions
- Search functionality with filters for location, price, amenities, etc.
- Booking system with confirmation
- User reviews and ratings
- Admin dashboard for managing listings and users

## 🛠️ Tech Stack

- **Backend:** Django
- **Database:** SQLite (Development) / PostgreSQL (Production)
- **Frontend:** HTML, CSS, JavaScript
- **Authentication:** Django Authentication System

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/alx_travel_app.git
   cd alx_travel_app
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS/Linux
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirement.txt
   ```

4. Run migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

6. Start the development server:
   ```bash
   python manage.py runserver
   ```

## 🏗️ Project Structure

```
alx_travel_app/
├── manage.py
├── requirement.txt
├── README.md
├── alx_travel_app/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── listings/
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py
    ├── tests.py
    ├── views.py
    └── migrations/
```

## 📝 Usage

### For Travelers
- Browse available listings
- Filter by location, price range, amenities
- View detailed information and photos
- Make bookings and manage your reservations

### For Property Owners
- Create and manage property listings
- Upload photos and details
- Set availability and pricing
- Review booking requests

### For Administrators
- Manage all listings and users
- Handle disputes and support requests
- View analytics and reports

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

Your Name - your.email@example.com

Project Link: [https://github.com/yourusername/alx_travel_app](https://github.com/yourusername/alx_travel_app)

---

Made with ❤️ for ALX Software Engineering Program