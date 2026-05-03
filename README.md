# Employee Management System

A full-stack Employee Management and HR dashboard built with Django REST Framework and React.js.

## Features

- Admin/User authentication
- Role-based access control
- Employee CRUD operations
- Profile image upload
- Employee profile view
- Search and filter employees
- Salary range filter
- Sorting by salary, name, and joining date
- Pagination
- Department summary
- Dashboard insights
- Excel export
- Responsive dashboard UI

## Tech Stack

### Backend
- Python
- Django
- Django REST Framework
- SQLite
- Token Authentication

### Frontend
- React.js
- Tailwind CSS
- Axios
- XLSX

## User Roles

### Admin
Admin can:
- Add employees
- Edit employees
- Delete employees
- View salary, email, phone
- Export employee data

### User
User can:
- View employee list
- View employee profile
- Search and filter employees

User cannot:
- Add employees
- Edit employees
- Delete employees
- View sensitive salary/contact details

## Project Structure

```text
backend/
├── api/
├── config/
├── frontend/
├── manage.py
├── requirements.txt
