# SMARTMART
online ordering & delivery platform.

<p align="center">
  <img src="smartmart/static/myapp/images/smlogo.jpg">
</p>


Python 3.12
Version 2.0

# 📦 Smart‑mart: Online Ordering & Delivery Platform
## 📖 Project Overview
Smart‑mart is an online product ordering and delivery platform built with Django, offering a location‑aware shopping experience. Customers can order groceries, fruits, vegetables, and daily essentials directly from nearby shops, supermarkets, or local stores.

It addresses the challenge of busy individuals lacking time for household shopping. By connecting users to nearby shops, Smart‑mart ensures faster deliveries without extra charges for speed, eliminating delays common in traditional e‑commerce systems.

-> Busy professionals with limited time for shopping

-> Families needing quick access to daily essentials

-> Local shops and supermarkets looking to expand their reach online

To provide a smarter, more efficient e‑commerce solution that saves time, reduces delivery distance, and supports local businesses while giving customers a seamless shopping and billing experience.
Smart‑mart offers a time‑saving, location‑aware delivery system that enhances convenience and efficiency in everyday shopping.

## Table of Contents
- Features
- Key Features
- Tech stack
- System Architecture
- Work Flow
- Repository Structure
- screenshots & Outcomes
- Installation Guide
- Authors & Contributors
- 

## Features

## 🚀 Features of Smart‑mart

- **Efficient Product Management**
  - Shop owners can add, edit, delete products.
  - Real‑time updates for availability and pricing.
  - Stock‑based enable/disable functionality.

- **User‑Friendly Shopping Experience**
  - Simple, intuitive interface for customers.
  - Search products and shops easily.
  - Detailed product descriptions, images, and reviews.

- **Enhanced Customer Convenience**
  - Orders fulfilled by nearby shops for faster delivery.
  - Multiple payment options (Cards, UPI, QR).
  - OTP verification for secure registration and delivery.

- **Delivery Management**
  - Dedicated delivery user login/registration.
  - Integrated maps for route optimization.
  - Real‑time order tracking and status updates.

- **Robust Payment Processing**
  - Secure gateways (e.g., Razorpay).
  - Signature verification for transactions.
  - Clear payment success and invoice pages.

- **Smart Assistant Integration**
  - Voice search and shopping queries.
  - Interactive modal assistant for navigation.
  - Saves customer time with quick responses.

- **Customer Feedback & Support**
  - Animated feedback forms for better UX.
  - Prompt handling of queries and complaints.

- **Security & Performance**
  - Role‑based access control (Customer, Shop Owner, Delivery User).
  - Encrypted sensitive data and secure payments.
  - Scalable to thousands of concurrent users with 99.9% uptime.
 
## 🚀 Key Features

### Customer Module

- User Registration & Login
- Nearby Shop Discovery
- Product Search
- Category-Based Shopping
- Cart Management
- Wishlist
- Online Payment
- Cash On Delivery
- Order Tracking
- OTP-Based Delivery Verification
- Smart AI Assistant

### Shop Owner Module

- Shop Registration
- Product Management
- Inventory Management
- Price Updates
- Product Availability Control
- Order Management
- Sales Dashboard

### Delivery Boy Module

- Delivery Boy Registration
- Order Pickup
- Navigation Support
- OTP Verification
- Delivery Status Updates

### Admin Module

- User Management
- Shop Management
- Product Management
- Delivery Management
- Reports & Analytics

---

## 🛠 Tech Stack

- **Backend Framework:** Django (Python)  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** MySQL  
- **Payment Gateway:** Razorpay (secure online transactions)  
- **Cloud Storage:** Cloudinary (for product images)  
- **Integration:** Python interface for database operations and billing  

## 🏗 System Architecture

Smart‑mart follows a **three‑role architecture** with clear responsibilities:

- **Customer**
  - Registers, logs in, and browses products.
  - Places orders from nearby shops/supermarkets.
  - Tracks delivery status and makes secure payments.

- **Shop Owner**
  - Manages product listings, categories, and availability.
  - Receives customer orders and generates digital invoices.
  - Updates stock in real‑time.

- **Delivery User**
  - Picks up orders from shops and delivers to customers.
  - Uses integrated maps for route optimization.
  - Updates order status and verifies delivery with OTP.

### 🔑 Core Components
- **Order Management** – Central entity connecting customers, shop owners, and delivery users.  
- **Payment Service** – Handles secure transactions via Razorpay.  
- **Order Cancel Service** – Allows flexible cancellation and refund handling.  
- **Cloud Storage** – Product images stored and managed via Cloudinary.  

## ⚙️ Workflow
1. Customer places an order → stored in system.  
2. Shop Owner receives order → prepares products and invoice.  
3. Delivery User picks up order → optimized route via maps.  
4. Payment processed securely → confirmation sent to customer.  
5. Order tracked until successful delivery.  

This architecture ensures **fast, secure, and location‑aware deliveries**, while supporting scalability and smooth integration between all roles.

## 📂 Repository Structure

```text
smartmart/                # Main project folder
│
├── smven/                # Virtual environment
│
├── smartmart/            # Core project folder
│   ├── sm_app/           # Main application
│   │   ├── migrations/   # Database migrations
│   │   ├── views.py      # Application views
│   │   ├── urls.py       # URL routing
│   │   ├── admin.py      # Admin configurations
│   │   ├── apps.py       # App configuration
│   │   ├── keys.py       # API keys (Razorpay, Cloudinary)
│   │   ├── models.py     # Database models
│   │   ├── tests.py      # Unit tests
│   │   ├── tokens.py     # Token management
│   │
│   ├── smartmart/        # Project settings
│   │   ├── __init__.py
│   │   ├── settings.py   # Django settings
│   │   ├── utils.py      # Utility functions
│   │   ├── wsgi.py       # WSGI entry point
│   │   ├── asgi.py       # ASGI entry point
│   │
│   ├── static/           # Static files
│   │   ├── myapp/
│   │       ├── images/   # Static images
│   │
│   ├── media/            # Media uploads (product images, etc.)
│   │
│   ├── templates/        # HTML templates
│   │   ├── *.html        # All frontend pages
│   │
│   ├── manage.py         # Django management script
│   ├── req.txt           # Requirements file
```


## screenshots & Outcomes
### customer Dashboard
<img width="1377" height="663" alt="Picture1" src="https://github.com/user-attachments/assets/a010a588-9879-454c-9183-e454db004687" />

### customer Login
<img width="1112" height="634" alt="Picture2" src="https://github.com/user-attachments/assets/68e5eeda-d092-4214-8efd-b10be5eb16cc" />

### Maps
<img width="1377" height="658" alt="Picture3" src="https://github.com/user-attachments/assets/65ae9865-51be-41e9-aa69-58a7ec4683ec" />

### Ex: Radhashop store categories
<img width="1074" height="754" alt="Picture4" src="https://github.com/user-attachments/assets/fbdcdeb5-718f-442c-91d1-b95720e1379a" />

### checkout page
<img width="1826" height="852" alt="Picture5" src="https://github.com/user-attachments/assets/f647f612-dc20-4e85-b7e1-bd68f7f57815" />

### Invoice(list of order items and item details)
<img width="921" height="816" alt="Picture6" src="https://github.com/user-attachments/assets/3c776536-7fba-4020-86ff-16bff3b862a1" />

### Adding Address to order
<img width="1378" height="611" alt="Picture7" src="https://github.com/user-attachments/assets/15cbd0ab-edd1-4931-bc1e-280029d14c9e" />
### order tacking
<img width="1379" height="517" alt="Picture8" src="https://github.com/user-attachments/assets/df965f2b-e053-4fc2-a422-c4d6c948ed79" />
### shop/store owner list of shops
<img width="926" height="428" alt="Screenshot 2026-06-27 074721" src="https://github.com/user-attachments/assets/330d021c-8a03-4a93-87f7-579b07ee6222" />

### A store categories and products
<img width="862" height="420" alt="Screenshot 2026-06-27 074742" src="https://github.com/user-attachments/assets/1b2f4943-90bd-4a3c-b733-1649054b404e" />
<img width="887" height="417" alt="Screenshot 2026-06-27 074812" src="https://github.com/user-attachments/assets/399780fa-1f43-4b39-a883-ef6fdc14da68" />

### Delivery Patner Dashboard
<img width="815" height="428" alt="Screenshot 2026-06-27 075000" src="https://github.com/user-attachments/assets/0baaa762-d0bb-4749-bf24-3a843effac4f" />

### Delivery Patner orders to pick from store
<img width="893" height="425" alt="Screenshot 2026-06-27 075036" src="https://github.com/user-attachments/assets/1fe55123-4ebf-4183-bfa9-98dd2490da9a" />

### Database
<img width="959" height="394" alt="image" src="https://github.com/user-attachments/assets/f3a1b9e4-2d4f-4f82-92b8-8e74fb04919d" />


## ⚙️ Installation Guide

Follow these steps to set up and run Smart‑mart locally:

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/smartmart.git
cd smartmart
```

### 2. Create Virtual Environment
```bash
python -m venv smven
```
### 3.Activate the environment:

#### Windows (PowerShell):
```bash
smven\Scripts\activate
```
#### Linux/MacOS:
```bash
source smven/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r req.txt
```
### 4. Configure Settings
```text
-> Add your Razorpay API keys in sm_app/keys.py.
-> Configure Cloudinary credentials for product image storage.
-> Update smartmart/settings.py with your database (MySQL) details
```
### 5. Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
### 6. Create Superuser (Admin Access)
```bash
python manage.py createsuperuser
```
### 7. Run Development Server
```bash
python manage.py runserver
```

Now open http://127.0.0.1:8000/ (127.0.0.1 in Bing) in your browser to access Smart‑mart.
✅ With this setup, you’ll have Smart‑mart running locally with Django, MySQL, Razorpay integration, and Cloudinary for image storage.


# Environment Variables
```env
SECRET_KEY=
DB_NAME=
DB_USER=
EMAIL_HOST=
RAZORPAY_KEY=
```
# Authors & Contributors
Shiva Kumar
Project Creator
