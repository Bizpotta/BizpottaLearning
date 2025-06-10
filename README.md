# 📘 BizpottaLearning

**BizpottaLearning** is a cloud-based Learning Management System (LMS) deployed for `learning.bizpotta.com` under the Bizpotta ecosystem. It supports course creation, user management, payment integration, and progress tracking for professional training and onboarding.

---

## 🚀 Features

- 🎓 Course and Curriculum Management
- 👥 Student & Instructor Roles
- 📈 Progress Tracking & Certifications
- 💳 Integrated Payments (Stripe, Cashfree)
- 🛠 Admin Panel for Full Control
- 📲 Mobile-Responsive Design

---

## 🌐 Live Site

🔗 [https://learning.bizpotta.com](https://learning.bizpotta.com)

---

## 📁 Project Structure

├── public/ # Public assets
├── resources/ # Blade views and assets
├── app/ # Core Laravel application (models, controllers)
├── routes/ # Web routes
├── database/ # Migrations & seeders
└── .env # Environment config (excluded in repo)


---

## 🧩 Tech Stack

- PHP 8.x
- Laravel 10
- MySQL
- Bootstrap / Tailwind CSS
- GitHub CI/CD
- Cloudways (Hosting)
- Cloudflare (DNS)

---

## ⚙️ Deployment

This app is deployed from [GitHub](https://github.com/Bizpotta/BizpottaLearning) using Git-based deployment on **Cloudways**.

---

## 📦 Setup Instructions (Local Dev)

```bash
git clone https://github.com/Bizpotta/BizpottaLearning.git
cd BizpottaLearning
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
