📦 Complete E-Commerce Website in Laravel 10

A full-featured, production-ready eCommerce platform built with Laravel 10.
Includes a modern frontend, powerful admin dashboard, secure authentication, and integrated payment gateway.

🌟 Features
🛒 Frontend

⚡ Progressive Web App (PWA) support

🎨 Modern & responsive UI

🛍️ Shopping cart & wishlist

🌟 Product reviews & multi-level comments

📦 Order tracking system

🔎 SEO-friendly URLs & metadata

💳 PayPal payment gateway

🔐 Social login (Google, Facebook, GitHub)

💬 Contact form, blog, categories

🛠️ Admin Dashboard

🔑 Role & permission management

📈 Sales analytics & dashboard insights

🛍️ Product, category & order management

📰 Blog & post management

🔔 Real-time notifications

🏷️ Coupon & discount system

📸 Banner, media, and slider manager

👤 User Dashboard

📦 Order history & tracking

⭐ Review & comment system

📝 Edit profile & manage addresses

❤️ Wishlist & saved items

🚀 Installation Guide
🔹 1. Clone Repository
git clone  
cd e-commerce

🔹 2. Install Backend & Frontend Dependencies
composer install
npm install

🔹 3. Environment Setup
cp .env.example .env
php artisan key:generate


Update your .env file with database details:

DB_DATABASE=your_db
DB_USERNAME=root
DB_PASSWORD=

🔹 4. Database Migration & Seeding
php artisan migrate --seed


If needed, manually import:

database/e-shop.sql

🔹 5. Link Storage
php artisan storage:link

🔹 6. Run the Application
php artisan serve


📍 Visit: http://localhost:8000

🔐 Admin Login Credentials
Email	            Password
admin@gmail.com     1111
