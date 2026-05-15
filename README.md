# 🎵 Purple Music

A lightweight, self-hosted web application to stream and organize your personal music library. Built with a responsive, dark-purple interface, it runs smoothly without heavy dependencies using **PHP** and **SQLite**.

> ✨ **Vibe-coded** with love and powered by AI.

![PHP](https://img.shields.io/badge/PHP-%3E%3D%207.4-777BB4?style=flat-square&logo=php)
![SQLite](https://img.shields.io/badge/Database-SQLite-003B57?style=flat-square&logo=sqlite)
![Vibe-Coded](https://img.shields.io/badge/Method-Vibe--Coded-8e44ad?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## ✨ Features

- **🚀 One-Click Install**: Automated setup wizard on the first run.
- **📱 Smart & Responsive UI**: Modern design optimized for desktop and mobile, featuring an app-like fullscreen player.
- **🎶 Multi-Format Support**: Plays and automatically calculates track length for `.mp3`, `.wav`, `.flac`, and `.ogg` files.
- **🏷️ ID3v2 Metadata Parser**: Automatically extracts title, artist, and embedded artwork from your MP3 files.
- **🖼️ Image Optimization**: Automatically resizes and converts covers to `.webp` to save bandwidth (requires PHP-GD extension).
- **🔀 Advanced Controls**: Shuffle, loop (track or queue), and dynamic queue management.
- **📂 Mixes & Playlists**: Create, edit, and share custom playlists among users.
- **🔒 Security & Control**: 
  - Session-based user/admin roles.
  - CSRF protection using secure tokens.
  - Rate-limiting on registration and file uploads.
  - Storage folders protected against arbitrary script execution via `.htaccess`.

---

## 🛠️ Prerequisites

To run Purple Music, you only need:
- A web server (Apache, Nginx, LiteSpeed, etc.)
- **PHP 7.4** or higher
- The following PHP extensions enabled:
  - `php-pdo_sqlite` (For the database)
  - `php-gd` *(Optional but highly recommended for image optimization)*

---

## 🚀 Installation & Deployment

1. **Clone the repository** into your web directory:
   ```bash
   git clone https://github.com/Axolat000/PurpleMusic
   cd purple-music
