# restaurant-booking-django
Full-stack restaurant reservation system built with Django, MySQL, and JavaScript for the Little Lemon project — includes booking API, form validation, and dynamic slot availability.
# 🍋 Little Lemon Booking System

This is a Django-based full stack project developed as part of the **Meta Back-End Developer Professional Certificate**.

## Features

- Booking form with validation
- Prevents duplicate reservations
- Fetches available slots dynamically
- JSON API for all bookings
- MySQL database support
- Uses Fetch API and JavaScript for dynamic UI

## Technologies

- Django
- MySQL
- JavaScript (Fetch API)
- HTML/CSS (provided starter templates)
- Pipenv

## Setup Instructions

```bash
git clone https://github.com/your-username/littlelemon-booking.git
cd littlelemon-booking
pipenv install
pipenv shell
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
