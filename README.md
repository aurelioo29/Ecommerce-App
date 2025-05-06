# 🛒 E-Commerce App

A **fullstack E-Commerce** application built entirely with **Next.js**, integrated with **Supabase** for authentication and database, and **Xendit** for payment processing.

## 🚀 Tech Stack

- **Fullstack Framework:** Next.js 14 (App Router)
- **Database & Auth:** Supabase
- **Payment Gateway:** Xendit
- **Styling:** Tailwind CSS
- **Deployment:** Vercel

## 📦 Features

- ✅ User registration & login (Supabase Auth)
- 🛍️ Product listing, detail, and filtering
- 🧺 Shopping cart & checkout system
- 💳 Online payment integration with Xendit
- 🛠️ Admin dashboard for managing products

## 🛠️ Getting Started

1. **Clone the repository:**

   ```bash
   https://github.com/aurelioo29/Ecommerce-App.git
   cd Ecommerce-App
   ```

2. **Install dependencies:**

   ```bash
   npm install

   # or

   yarn install
   ```

3. **Configure environment variables:**

   Salin file `.env.example` ke .env lalu isi dengan nilai dari Supabase dan Xendit:

   ```bash
   cp .env.example .env
   ```

4. **Run the development server:**

   ```bash
   npm run dev

   # or

   yarn dev
   ```

## 📁 Folder Structure

```bash
📦 Ecommerce-App
├── 📂 lib              # Utility functions dan helper (misalnya untuk Supabase, Xendit, dsb.)
├── 📂 prisma           # Konfigurasi Prisma ORM dan file schema database
├── 📂 public           # File statis seperti gambar, icon, dsb.
├── 📂 src              # Berisi kode utama aplikasi (app router, komponen, style, dsb.)
├── .env                # Environment variables utama
├── .env.example        # Contoh template variabel lingkungan
├── tailwind.config.js  # Konfigurasi Tailwind CSS
├── next.config.js      # Konfigurasi Next.js
├── package.json        # Berisi dependencies dan script npm/yarn
└── README.md           # Dokumentasi proyek
```
