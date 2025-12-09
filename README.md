# 🚀 Portfolia.dev - The Ultimate SaaS Portfolio Builder

[![Portfolia Banner](assets/banner.png)](https://portfolio-popm.onrender.com)

> **Stop building from scratch. Design. Export. Get Hired.**
>
> A secure, full-stack SaaS platform that allows professionals to generate high-end 3D & Minimal Portfolios and Harvard-style PDF Resumes in minutes.

<div align="center">

[![Live Demo](https://img.shields.io/badge/🔴_Live_Demo-Online-success?style=for-the-badge)](https://portfolio-popm.onrender.com)
[![Python](https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-Framework-black?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Stripe](https://img.shields.io/badge/Stripe-Payments-635bff?style=for-the-badge&logo=stripe&logoColor=white)](https://stripe.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

</div>

---

## 🌟 Overview

Portfolia is not just a template designed for developers; it's a complete, production-ready **SaaS ecosystem**. It solves the problem of creating professional, deployable personal websites without spending hours coding them from zero.

It combines a powerful real-time editor with secure backend infrastructure, handling everything from user authentication and database management to payments and PDF generation.

![Core Features](assets/features_grid.png)

---

## ✨ Key Features

### 🎨 The Creator Studio (Real-Time Editor)
A sophisticated split-screen interface. Users input data on the left, and the portfolio updates instantly on the right. No page reloads required.

* **Adaptive Themes:** Switch instantly between **Cyberpunk** (3D animated background for devs) and **Minimal Architect** (clean grid for designers).
* **Dynamic Visuals:** Real-time accent color picker and typography adjustments.

![Editor UI](assets/editor_ui.png)

### 📄 Professional Exports
* **PDF Generation Engine:** Utilizes `WeasyPrint` to render pixel-perfect, ATS-friendly PDF CVs directly from the HTML template. includes dynamic font-sizing options (Compact to Huge).
* **100% Code Ownership (Premium):** Users can download the raw, unminified HTML/CSS file to host freely on GitHub Pages, Netlify, or Vercel.

### 💳 SaaS Monetization & Security
Integrated **Stripe Checkout** flow for friction-less upgrades to the Lifetime Pro plan.

* **Secure Authentication:** `Flask-Bcrypt` hashing and secure session management.
* **Production Security:** Implements CSP headers via `Flask-Talisman` and rate-limiting via `Flask-Limiter` to prevent abuse.
* **SMTP Transactional Emails:** Powered by **Resend** for reliable delivery.

![Pricing Model](assets/pricing.png)

---

## 🛠️ Tech Stack Under the Hood

| Category | Technologies |
| :--- | :--- |
| **Backend Framework** | Python 3.11, Flask 3.0 |
| **Database & ORM** | PostgreSQL (Production), SQLAlchemy |
| **Frontend** | HTML5, Modern JavaScript (Vanilla), TailwindCSS |
| **PDF Engine** | WeasyPrint |
| **Payments & Billing** | Stripe API |
| **Email Infrastructure**| Resend SMTP |
| **Deployment** | Render Cloud PaaS |

---

## 🚀 Local Development Setup

Want to run it locally? Follow these steps.

### Prerequisites
* Python 3.10 or higher
* Git
* *(Optional but recommended)* A virtual environment

### 1. Clone the repository
```bash
git clone [https://github.com/Vdamoulas/portfolio-saas.git](https://github.com/Vdamoulas/portfolio-saas.git)
cd portfolio-saas
