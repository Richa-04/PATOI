# Pet Store Website (PATOI)

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-3.2%2B-green?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![License](https://img.shields.io/badge/License-Academic-lightgrey?style=for-the-badge)](#)
[![GitHub Workflow](https://img.shields.io/badge/CI/CD-GitHub%20Actions-brightgreen?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/)

*An all-in-one Django-based platform connecting pet owners, retailers, and veterinarians*

[Features](#-features) • [Installation](#-installation) • [Technology Stack](#-technology-stack) • [Documentation](#-database-schema)

</div>

---

## 📋 Project Overview

**PATOI** is a comprehensive Django web application that serves as a complete ecosystem for pet-related services. The platform seamlessly connects customers with pet product retailers and veterinary professionals, while providing a vibrant social space for pet owners to share and celebrate their beloved companions.

**Project Details:**
- **Submitted:** December 2021
- **Developed by:** Richa Padhariya, Jenil Shyara
- **Institution:** Tops Career Center

---

## ✨ Features

### 🛍️ Customer Features

- **Account Management** – Secure user registration and authentication
- **Shopping Experience** – Product search with category-based filtering
- **Purchase Tools** – Shopping cart and wishlist functionality
- **Payments** – Integrated online payment system
- **Order Tracking** – Complete order history and status updates
- **Veterinary Services** – Browse vet profiles and book appointments
- **Social Features** – Upload, view, and like pet photos
- **Feedback System** – Share product reviews and website feedback

### 🏪 Retailer Features

- **Business Profile** – Registration and comprehensive profile management
- **Product Management** – Add, edit, and organize product listings
- **Order Processing** – View and manage customer orders
- **Financial Tracking** – Payment history and revenue analytics
- **Store Customization** – Edit shop descriptions and details

### 👨‍⚕️ Veterinarian Features

- **Professional Profile** – Doctor registration and credentials management
- **Appointment System** – View and manage appointment requests
- **Schedule Control** – Approve or decline bookings
- **Profile Updates** – Edit professional descriptions and specialties

### 🔧 Admin Features

- **User Management** – Oversee doctors, retailers, and customers
- **Order Oversight** – Monitor and manage all transactions
- **Content Moderation** – Review uploaded pet photos
- **Feedback Review** – Analyze customer feedback and suggestions
- **System Control** – Complete platform monitoring and management

---

## 🛠️ Technology Stack

### Frontend
- **HTML5** – Structure and semantic markup
- **CSS3** – Modern styling and animations
- **Bootstrap** – Responsive design framework
- **JavaScript** – Dynamic and interactive features

### Backend
- **Python** – Core programming language
- **Django** – High-level web framework
- **SQLite** – Development database
- **MySQL** – Production database (optional)

---

## 🚀 Installation

### Prerequisites

Ensure you have the following installed:
- Python 3.8 or higher
- pip (Python package manager)
- Virtual environment tool (recommended)

### Setup Steps

**1. Clone the repository**
```bash
git clone https://github.com/yourusername/pet-store-website.git
cd pet-store-website
```

**2. Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

**3. Install dependencies**
```bash
pip install django
pip install pillow
```

**4. Run migrations**
```bash
python manage.py makemigrations
python manage.py migrate
```

**5. Create a superuser (admin)**
```bash
python manage.py createsuperuser
```

**6. Run the development server**
```bash
python manage.py runserver
```

**7. Access the application**
- Main application: `http://127.0.0.1:8000/`
- Admin panel: `http://127.0.0.1:8000/admin/`

---

## 📊 Database Schema

### Main Tables

| Table | Description |
|-------|-------------|
| **User** | Authentication and role management |
| **Customer** | Customer profile information |
| **Doctor** | Veterinarian profiles and credentials |
| **Retailer** | Seller profiles and business details |
| **Product** | Product catalog and inventory |
| **Cart** | Shopping cart items |
| **Order** | Purchase orders and transactions |
| **Appointment** | Veterinary appointment bookings |
| **Payment** | Payment records and transaction history |
| **Gallery** | User-uploaded pet photos |
| **Feedback** | Customer reviews and feedback |

---

## 🧪 Testing

The project includes comprehensive test cases covering all user roles and functionalities.

**Run tests using:**
```bash
python manage.py test
```

---

## 🔮 Future Enhancements

- 📱 Mobile application development (iOS & Android)
- 💬 Real-time chat system for customer support
- 📹 Video calling integration for veterinary consultations
- 💭 Comment system on pet photos
- 📥 Photo download functionality
- 📧 Email notifications for orders and appointments
- 💳 Multiple payment gateway integration
- 🌐 Multi-language support

---

## ⚠️ Current Limitations

- Audio-only communication with veterinarians
- No direct messaging with doctors
- Limited social interaction (no commenting on posts)
- No download feature for pet photos

---

## 🧰 Version Compatibility

| Python Version | Django Version |
|----------------|----------------|
| 3.8+ | 3.2+ |
| 3.9+ | 4.x |

---
