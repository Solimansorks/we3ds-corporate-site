# We3ds Corporate Bilingual Website (Laravel)

This is the official bilingual (Arabic/English) corporate website for **We3ds** — a digital design and smart solutions agency. The website is built using Laravel and includes a custom admin dashboard for content management.

---

## 🌐 Features

- Multi-language support (Arabic 🇸🇦 / English 🇬🇧)
- Mobile-first responsive layout with Tailwind CSS
- Admin dashboard for managing:
  - Projects / Portfolio
  - Services
  - Testimonials
  - Contact messages (inbox)
  - Blog posts
  - Certificates
- SEO friendly structure
- File & image management using Spatie Media Library
- Export data to PDF and Excel
- Google Maps integration
- Protected admin routes with authentication
- Light and Dark mode ready

---

## 🛠️ Installation Steps

```bash
git clone https://github.com/your-username/we3ds-corporate-site.git
cd we3ds-corporate-site

cp .env.example .env
composer install
npm install && npm run dev

php artisan key:generate
php artisan migrate --seed
php artisan storage:link
