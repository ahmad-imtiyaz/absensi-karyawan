<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<h1 align="center">Absensi Karyawan – Laravel Backend Learning Project</h1>

<p align="center">
  Project pembelajaran backend Laravel berbasis studi kasus nyata: <b>Sistem Absensi Karyawan</b>.
</p>

---

## 🎯 Tujuan Project

Project ini dibuat sebagai **media belajar backend Laravel secara bertahap dan realistis**, dengan fokus pada:

-   Autentikasi & otorisasi (Auth, Role, Middleware)
-   Keamanan akun (Email Verification, Reset Password)
-   Manajemen user (Admin & Karyawan)
-   Best practice backend Laravel

Bukan sekadar CRUD, tapi **alur backend seperti aplikasi production**.

---

## 🚀 Tech Stack

-   **Laravel 12**
-   **Laravel Breeze (Blade)**
-   **MySQL**
-   **Tailwind CSS**
-   **Mailtrap (Email Testing)**
-   **PHP 8.2+**

---

## 📌 Fitur yang Sudah Diimplementasikan

### 🔐 Authentication & Security

-   [x] Register & Login
-   [x] Middleware `auth`
-   [x] Email Verification
-   [x] Forgot Password (Reset via Email)
-   [x] Session Management

### 👥 User & Role

-   [x] Role User (Admin & Karyawan)
-   [x] Helper `isAdmin()` di User Model
-   [x] Admin Middleware
-   [x] Admin Account via Seeder

### 📧 Email System

-   [x] Mailtrap Integration (Local Development)
-   [x] Reset Password Email
-   [x] Email Verification Link

---

## 🧠 Konsep yang Dipelajari

Project ini menekankan **pemahaman konsep**, bukan sekadar jalan:

-   Cara kerja Auth Laravel (Guard & Session)
-   Flow Email Verification
-   Flow Reset Password Token
-   Middleware vs Policy
-   Seeder untuk data penting (Admin)
-   Perbedaan Local vs Production Email

---

## 🛠️ Instalasi & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/username/absensi-karyawan.git
cd absensi-karyawan
```
