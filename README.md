<div align="center">

<img src="favicon.svg" width="80" height="80" alt="X-Encoder Logo">

# ⚡ X-Encoder

**Encode, obfuscate & protect your HTML / JS / CSS and Python files — right in your browser.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-x--encoder.netlify.app-FF6B00?style=for-the-badge&logo=netlify&logoColor=white)](https://x-encoder.netlify.app/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Made With](https://img.shields.io/badge/Made%20With-HTML%20%2F%20JS-orange?style=for-the-badge&logo=javascript)]()

</div>

---

## 🔥 Features

- 🌐 **HTML / JS / CSS Encoder**
  - Minify code (strip whitespace & comments)
  - Base64 encode wrapped in `eval(atob())` runner
  - Variable name obfuscation
  - String splitting (Heavy mode)
  - 3 obfuscation levels: **Light / Medium / Heavy**

- 🐍 **Python Encoder**
  - Base64 + `exec()` runner format
  - Marshal / bytecode loader format
  - Multi-layer double encoding
  - Anti-read junk header injection

- 🎨 **VS Code–style Editor**
  - Syntax highlighting (HTML, JS, CSS, Python)
  - Line numbers, active line highlight, bracket matching
  - Drag & drop or file upload support
  - Auto language detection

- 📦 **Output**
  - Download encoded file instantly
  - Copy to clipboard
  - File size stats (original → encoded)

---

## 🚀 Live Demo

👉 **[https://x-encoder.netlify.app/](https://x-encoder.netlify.app/)**

---

## 📸 Preview

> Dark theme · VS Code editor · Mobile-first UI

---

## 🛠️ Usage

1. Open the [live site](https://x-encoder.netlify.app/)
2. Choose mode: **HTML/JS/CSS** or **Python**
3. Drop your file or paste code into the editor
4. Configure encoding options
5. Click **Encode Now**
6. Download or copy the encoded output

---

## 📁 Self-Host

```bash
git clone https://github.com/M41NUL/X-Encoder.git
cd X-Encoder
# Open index.html in any browser — no server needed
```

> 100% client-side. No backend. No data sent anywhere.

---

## 📋 Encoding Methods

| Method | Language | Description |
|---|---|---|
| Minify | JS / CSS | Remove whitespace & comments |
| Base64 + eval | JS | `eval(atob("..."))` wrapper |
| Variable Rename | JS | Obfuscate all variable names |
| String Split | JS (Heavy) | Break strings into concatenations |
| Base64 + exec | Python | `exec(compile(base64.b64decode(...)))` |
| Marshal | Python | Bytecode compile + exec |
| Multi-layer | Python | Double base64 encoding |

---

## 👤 Developer

**Md. Mainul Islam (MAINUL-X)**

[![GitHub](https://img.shields.io/badge/GitHub-M41NUL-181717?style=flat-square&logo=github)](https://github.com/M41NUL)
[![Telegram](https://img.shields.io/badge/Telegram-@mdmainulislaminfo-2CA5E0?style=flat-square&logo=telegram)](https://t.me/mdmainulislaminfo)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Chat-25D366?style=flat-square&logo=whatsapp)](https://wa.me/8801308850528)
[![Email](https://img.shields.io/badge/Email-devmainulislam@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:devmainulislam@gmail.com)

---

<div align="center">

© 2026 X-Encoder — MAINUL-X. All rights reserved.

</div>
