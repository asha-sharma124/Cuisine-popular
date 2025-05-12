Yum Yard - Online Food Delivery Website

🚀 Project Overview

Yum Yard is a full-featured online food delivery website built using React for the frontend and Django for the backend. It provides a seamless platform for users to browse food items, add them to a cart, place orders, and track their order status. The platform also supports vendor registration and Razorpay payment integration.

🛠️ Tech Stack

Frontend: React, CSS

Backend: Django, Django REST Framework

Database: SQLite

Payment Gateway: Razorpay

✅ Features

User Authentication (Login, Register)

Add to Cart Functionality

Razorpay Payment Integration

Order Tracking with Timer

Vendor Registration (New vendors can register and sell food items)

Sending Email to Host (Admin) for Vendor Registration

📌 Installation

Prerequisites

Javascript (for React)

Python (for Django)

SQLite (for database)

Razorpay Account (for payment integration)

Backend (Django)

Clone the repository and navigate to the backend folder:

git clone https://github.com/your-username/Cuisine-popular.git
cd backend

Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Set up PostgreSQL and apply migrations:

python manage.py migrate

Run the development server:

python manage.py runserver

Frontend (React)

Navigate to the frontend folder:

cd ../frontend

Install dependencies:

npm install

Create a .env file and add your Razorpay API key:

REACT_APP_RAZORPAY_KEY=your_razorpay_key

Start the React development server:

npm start/ npm run dev

📬 Sending Emails for Vendor Registration

When a new vendor registers, an email is sent to the host/admin for verification.

Email configuration is managed in Django settings.

⚡ Usage

Register as a user or vendor.

Browse food items and add them to the cart.

Proceed to checkout and complete the payment via Razorpay.

Track your order status.

