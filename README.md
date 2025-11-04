# 🔐 cXRat — Local 2FA (Two-Factor Authentication) Demo [Educational Project]

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Flask](https://img.shields.io/badge/Framework-Flask-green.svg)
![License](https://img.shields.io/badge/License-Educational-lightgrey.svg)

> ⚠️ **Educational Use Only** — This project is a local demo built for learning and teaching secure authentication workflows.  
> Do **not** use this configuration in production environments.

---

## 💡 Overview
**cXRat** is a lightweight, local **Two-Factor Authentication (2FA)** demo built using **Python and Flask**.  
It showcases how Time-based One-Time Passwords (**TOTP**) work end-to-end — from QR enrollment to token validation — while exploring security trade-offs such as clock drift, replay protection, and secret handling.

This project is designed for **educational and research purposes only**, making it ideal for cybersecurity students, developers, and trainers to understand how modern authentication works.

---

## ⚙️ Features
- 🧩 **QR Enrollment:** Generates provisioning URIs and QR codes for Google Authenticator / Authy.  
- ⏱️ **TOTP Verification:** Implements `pyotp` with ±30s drift tolerance.  
- 🔁 **Replay Protection:** Prevents OTP reuse within the same 30-second window.  
- 🧠 **Local Persistence:** Stores user data securely using SQLite (demo database).  
- 🧾 **Minimal Cyber UI:** Simple HTML/CSS/JS frontend for easy learning.  
- 🔒 **Security-Conscious Design:**  
  - `.env.template` for secrets  
  - Local certificate generation  
  - “EDUCATION ONLY” warnings  

---

## 🛠️ Tech Stack
- **Backend:** Python, Flask  
- **Libraries:** PyOTP, Pillow, QRCode  
- **Database:** SQLite (Demo)  
- **Frontend:** HTML, CSS, JavaScript  
- **Version Control:** Git & GitHub  




