<p align="center">
  <img src="(https://raw.githubusercontent.com/avst-dev/avst-dev/refs/heads/main/wmremove-transformed.jpeg)" width="100%">
</p>

<p align="center">
  <h1 align="center">🕵️‍♂️ AVST PROJECT</h1>
  <p align="center">
    <strong>The Next-Generation Digital Forensics & Security Auditing Framework</strong>
    <br />
    <a href="#-dokumentasi">Jelajahi Dokumen</a> •
    <a href="#-fitur-unggulan">Fitur Utama</a> •
    <a href="#-kontribusi">Kontribusi</a>
  </p>
</p>

<p align="center">
  <img src="https://img.shields.io/github/languages/top/avst-dev/avst-project?style=for-the-badge&color=00ff00" alt="Top Language">
  <img src="https://img.shields.io/badge/STRATA-2_%26_3_AVAILABLE-blue?style=for-the-badge" alt="Strata Availability">
  <img src="https://img.shields.io/badge/SECURITY-AUDIT_READY-red?style=for-the-badge" alt="Security Ready">
</p>

---

## 🌌 Tentang AVST
**AVST Project** adalah ekosistem modular yang dirancang untuk kebutuhan *cybersecurity* tingkat lanjut. Proyek ini mengintegrasikan alat audit kerentanan otomatis dengan mesin investigasi forensik digital yang presisi, dirancang khusus untuk berjalan optimal di lingkungan Linux dan perangkat Android yang telah dimodifikasi.

> **Catatan:** Modul Digital Forensics pada proyek ini dioptimalkan khusus untuk pengoperasian pada **Strata 2** dan **Strata 3**.

---

## ✨ Fitur Unggulan

| Modul | Fungsi Utama | Status |
| :--- | :--- | :--- |
| **Vulnerability Scanner** | Identifikasi SQLi, XSS, dan miskonfigurasi secara otomatis. | `Stable` |
| **Forensic Engine** | Deep data recovery dan analisis artefak sistem pada Strata 2/3. | `Enchanced` |
| **Network Bridge** | Integrasi WebSocket & Cloudflare Tunnel untuk bypass restriksi. | `Active` |
| **Ghost Mode** | Operasi senyap dengan jejak log minimal pada sistem target. | `Beta` |

---

## 🛠️ Arsitektur Teknologi
Proyek ini dibangun di atas pondasi yang mengutamakan performa tinggi dan keamanan data:

*   **Core Engine:** [Golang](https://go.dev/) (untuk konkurensi dan kecepatan eksekusi).
*   **Scripts & Automation:** [Python 3.10+](https://python.org).
*   **Infrastructure:** Cloudflare Workers & WebSocket Tunneling.
*   **Environment:** Debian 13 (Trixie) & Kali Linux via Proot-Distro.

---

## 🚀 Memulai Cepat

### Prasyarat
- Git & Python 3.x
- Go 1.21+ (untuk kompilasi modul utama)
- Akses Root/Sudo (disarankan)

### Instalasi
```bash
# 1. Clone repositori dengan submodul
git clone --recursive [https://github.com/avst-dev/birdchat.git](https://github.com/avst-dev/birdchat.git)

# 2. Masuk ke ruang kerja
cd avst-project

# 3. Inisialisasi Environment
make install
