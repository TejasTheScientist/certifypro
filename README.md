# 🎓 CertifyPro

CertifyPro is a premium, free online certificate generator. It allows organizations, companies, instructors, and event coordinators to instantly create professional, high-resolution certificates for internships, course completions, training programs, event participation, and achievements.

## 🔗 Live Demo
You can access and use the live website directly here:
👉 **[https://tejasthescientist.github.io/certifypro/](https://tejasthescientist.github.io/certifypro/)**

---

## ✨ Features

- **5 Specialized Generators:**
  - 🏢 **Internship Certificates** (custom roles, departments, company details)
  - 📚 **Course Certificates** (custom grades, scores, hours)
  - 🏫 **Training Certificates** (custom bootcamps, trainer names)
  - 🏆 **Participation Certificates** (custom events, hackathons, webinars)
  - 🌟 **Appreciation Certificates** (employee recognition, volunteers, contributors)
- **7+ Premium Design Templates:** Crafted with elegant styling, rich HSL color palettes, and classic typography.
- **Instant Export Options:** Download instantly as print-ready **A4 Landscape PDF** files or high-resolution **PNG images**.
- **No Sign-Up / No Login:** Full access to all features immediately with zero registration.
- **100% Client-Side Processing:** All data entries and logo uploads are processed directly in your web browser. No data is ever sent to or stored on a server, ensuring 100% privacy.
- **Branding Personalization:** Upload custom logos, signature images, and adjust signature details.
- **Rich User Experience:** Modern layout supporting **Glassmorphism**, responsive grids, micro-animations, and a sleek **Dark/Light Mode** toggle.

---

## 🛠️ Technology Stack & Libraries

- **Frontend Core:** Pure HTML5, Semantic CSS3 (custom CSS design system tokens), and Vanilla JavaScript.
- **Typography:** Premium fonts served via Google Fonts (`Cinzel`, `DM Sans`, `Cormorant Garamond`, `EB Garamond`, `Great Vibes`).
- **PDF Generation:** [jsPDF](https://github.com/parallax/jsPDF) (v2.5.1) for generating vectorized, high-fidelity PDF documents.
- **Image Generation:** [html2canvas](https://github.com/niklasvh/html2canvas) (v1.4.1) for rendering HTML DOM elements into high-resolution PNG downloads.

---

## 🚀 Running Locally

Since CertifyPro is a fully static web application, you do not need any compilation or build steps to run it locally.

### Method 1: Double-click (Easiest)
1. Clone this repository:
   ```bash
   git clone https://github.com/TejasTheScientist/certifypro.git
   ```
2. Navigate into the directory and double-click the [index.html](index.html) file to open it in your preferred web browser.

### Method 2: Local HTTP Server (Recommended)
To prevent CORS restrictions during local asset loading:
1. If you have **Node.js** installed, run:
   ```bash
   npx serve .
   ```
   Or if you have **Python** installed:
   ```bash
   python -m http.server 8000
   ```
2. Open your browser and navigate to `http://localhost:3000` (for node) or `http://localhost:8000` (for python).

---

## 📄 License

This project is open-source and free to use for personal, academic, and commercial certificate generation.
