# 🔍 Password Leak Checker

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge&logo=github-pages)](https://edwinyaboy.github.io/password-leak-checker/) 
[![Open Source](https://img.shields.io/badge/Open%20Source-MIT-green?style=for-the-badge)](https://github.com/edwinyaboy/password-leak-checker) 
[![Secure](https://img.shields.io/badge/Secure-Client%20Side-blue?style=for-the-badge)](https://edwinyaboy.github.io/password-leak-checker/)
[![HIBP Check](https://img.shields.io/badge/HIBP-Breach%20Check-orange?style=for-the-badge)](https://haveibeenpwned.com/)

**Open Source | Secure | Client-Side | HIBP Breach Check**

---

## 🎯 Features

- 🛡️ **HIBP Breach Check**  
  Checks passwords against [Have I Been Pwned](https://haveibeenpwned.com/) securely using the k-Anonymity API — only SHA-1 hashes are sent.

- 🔒 **Sanitized & Validated Input**  
  Passwords are trimmed, validated (6–128 characters), and sanitized before checking.

- ✅ **Safe & Unsafe Feedback**  
  Clearly shows if a password is safe or has been breached, including the number of times seen in breaches.

- 🌐 **Client-Side Only**  
  Runs entirely in the browser — no passwords are sent to your server.

- 📱 **Responsive & Themed**  
  Dark theme with blurred card design, gradient buttons, and toast notifications — works on mobile and desktop.

- ⚡ **Fast & Lightweight**  
  Minimal dependencies (only CryptoJS for future-proof hashing support).

---

## 💻 Example Results

| Password           | Breach Status            |
|------------------|:-----------------------:|
| `T8y$3qW!aP2#`    | ✅ Safe                 |
| `password123!`    | ⚠️ Seen 12,345 times    |
| `F@9m*7bKz!Dq`    | ✅ Safe                 |

> **Note:** Passwords above are examples — live passwords are checked securely against HIBP in real time.

---

## 🔗 Try It Live

[Click here to check your password!](https://edwinyaboy.github.io/password-checker/)

---

## 🛠️ License

MIT License — free to use, modify, and share.
