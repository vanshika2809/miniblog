# Django Blog Project with User Authentication

This project is a simple blog application built with Django, featuring user authentication. Users can sign up, log in, and manage their blog posts from a dashboard. The application includes basic CRUD operations for blog posts and different views for home, about, contact, and user dashboard.

## Features
- User Authentication (Sign Up, Login, Logout)
- Add, Update, and Delete Blog Posts
- View All Posts on the Home Page
- Separate User Dashboard
- Basic About and Contact Pages

## Project Structure
- `miniblog/`: Project settings and URL configuration
- `blog/`: Main app containing models, forms, views, and templates

## Getting Started
1. Clone the project from GitHub
2. Create and activate a virtual environment
3. Install Django with `pip install django`
4. Perform migrations with `python manage.py makemigrations` and `python manage.py migrate`
5. Run the server with `python manage.py runserver`
