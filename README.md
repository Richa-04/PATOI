# Pet Store Website (PATOI)  

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)  
[![Django](https://img.shields.io/badge/Django-3.2%2B-green)](https://www.djangoproject.com/)  
[![License](https://img.shields.io/badge/License-Academic-lightgrey)](#)  
[![GitHub Workflow](https://img.shields.io/badge/CI/CD-GitHub%20Actions-brightgreen)](https://github.com/)  

---

## 📋 Project Overview

PATOI is a Django-based web application that provides an all-in-one solution for pet-related services. The platform connects customers with pet product retailers and veterinarians, while also offering a social space for pet owners to share photos of their pets.  

- **Project Submitted:** December 2021  
- **Developed by:** Richa Padhariya, Jenil Shyara  
- **Institution:** Tops Career Center  

---

## ✨ Features

### 🛍️ Customer Features
- User registration and authentication
- Product search and category-based filtering
- Shopping cart and wishlist functionality
- Online payment system
- Order history tracking
- View veterinarian profiles
- Book appointments with veterinarians
- Upload and like pet photos
- Product and website feedback

### 🏪 Retailer Features
- Retailer registration and profile management
- Add and manage products
- View customer order details
- Payment history and order tracking
- Shop description management

### 👨‍⚕️ Veterinarian Features
- Doctor registration and profile management
- View and manage appointment requests
- Approve or decline appointments
- Profile description editing

### 🔧 Admin Features
- Manage doctors, retailers, and customers
- Order management
- View uploaded pet photos
- Review customer feedback
- System-wide control and monitoring

---

## 🛠️ Technology Stack

**Frontend**
- HTML5 – Structure and content
- CSS3 – Styling and layout
- Bootstrap – Responsive design framework
- JavaScript – Interactive functionality

**Backend**
- Python – Programming language
- Django – Web framework
- SQLite – Built-in database (development)
- MySQL – Production database (optional)

---

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Virtual environment (recommended)

### Setup Steps
1. **Clone the repository**
```bash
git clone https://github.com/yourusername/pet-store-website.git
cd pet-store-website
```
2. **Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. **Install dependencies**
```bash
pip install django
pip install pillow
```
4. **Run migrations**
```bash
python manage.py makemigrations
python manage.py migrate
```
5. Create a superuser (admin)
```bash
python manage.py createsuperuser
```
6. Run the development server
```bash
python manage.py runserver
```
7. Access the application
Open your browser and navigate to http://127.0.0.1:8000/
Admin panel: http://127.0.0.1:8000/admin/

##📊 Database Schema
Main Tables
  User – Authentication and role management  
  Customer – Customer profile information
  Doctor – Veterinarian profiles
  Retailer – Seller profiles
  Product – Product catalog
  Cart – Shopping cart items
  Order – Purchase orders
  Appointment – Veterinary appointments
  Payment – Payment records
  Gallery – Pet photos
  Feedback – User feedback

## 🧪 Testing
The project includes comprehensive test cases for all user roles.
Run tests using:
bash
```
python manage.py test
```
---
##🔮 Future Enhancements

Mobile application development
Real-time chat system
Video calling for veterinary consultations
Comment system on pet photos
Photo download functionality
Email notifications for orders and appointments
Multiple payment gateway integration

---

##⚠️ Current Limitations

Audio-only communication with veterinarians
No direct chat with doctors
No commenting on posts
No post download functionality

---

##🧰 Python & Django Version Compatibility
Python Version	Django Version
3.8+	3.2+
3.9+	4.x

