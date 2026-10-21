# 🚀 Assignment 1: Business Landing Page (Elementor)

> **Course Assignment:** WordPress Tutorials – Assignment 1  
> **Topic:** Single-Page Business Landing Page using Elementor Free  
> **Student / Author:** arpit294  
> **Reference Document:** [Assignment 1 Google Doc](https://docs.google.com/document/d/1WLsoVaNIPM3JrBSm3uA1JlhMKZOA6OabJMAqrY1ZuA8/edit?tab=t.0#heading=h.uiekik2pdw9f)

---

## 🎯 Objective
Learn and practice the Elementor page builder interface—including sections, columns, typography, styling, and basic widgets—by designing a high-converting, single-page business landing page.

---

## 🏢 Business Type
- **Category:** Digital Agency & Web Development Services
- **Design Philosophy:** Clean, modern, conversion-focused, and 100% mobile responsive.

---

## 📄 Mandatory Page Sections

### 🔥 1. Hero Section
- **Heading:** High-impact business headline communicating core value proposition.
- **Description:** Concise, compelling introductory subtext.
- **Call-To-Action (CTA):** Prominent button guiding visitors to get in touch.
- **Visuals:** High-resolution professional background image with gradient overlay.

### 👤 2. About Section
- **Layout:** Two-column responsive layout (Text + Visual Media).
- **Content:** Crisp 2–3 line company introduction detailing agency expertise.
- **Media:** Featured image illustrating team and agency capability.

### 🧩 3. Services Section
- **Services Displayed:** Exactly **TWO** core featured services:
  1. *Custom Web Development & WordPress Solutions*
  2. *Digital Strategy & Responsive UI/UX Design*
- **Widgets:** Built using **Icon Box** / **Image Box** widgets for readability and visual balance.

### 📞 4. Contact Section
- **Interactive Form:** Functional contact form powered by **WPForms**.
- **Contact Details:** Direct text format communication channels:
  - 📧 Email: Contact / Inquiries
  - 📱 Phone: Business Direct Line
  - 📍 Location: Office Address / Service Coverage

---

## 📱 Responsiveness & Standards
- Fully optimized for **Desktop**, **Tablet**, and **Mobile** viewports.
- Automatic column stacking on smaller screens.
- Scaled typography and button touch-targets adhering to mobile-first usability.

---

## 📂 Repository Contents
```text
├── assignment1_database.sql   # Complete MySQL database export for Assignment 1
├── assignment1.rtf            # Submission report document with embedded screenshots
├── wp-content/
│   ├── plugins/
│   │   ├── elementor/         # Elementor Page Builder (Free)
│   │   ├── wpforms-lite/      # Contact Form Plugin
│   │   ├── header-footer-elementor/
│   │   └── classic-editor/
│   ├── themes/
│   │   └── astra/             # Astra Lightweight WordPress Theme
│   └── uploads/               # Project media and image assets
├── wp-config.php              # Pre-configured local WordPress configuration
├── index.php
└── README.md                  # Complete project documentation
```

---

## ⚙️ Installation & Setup (Laragon / Localhost)

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/arpit294/assignment-1-business-landing-page.git
   ```
   *(Or place into your `laragon/www/assignment-1-business-landing-page` directory)*

2. **Database Setup:**
   - Create a MySQL database (e.g. `assignment1_db` or `word`).
   - Import `assignment1_database.sql` into your database:
     ```bash
     mysql -u root -p assignment1_db < assignment1_database.sql
     ```

3. **Configure `wp-config.php`:**
   - Verify DB credentials match your local MySQL server:
     ```php
     define( 'DB_NAME', 'assignment1_db' );
     define( 'DB_USER', 'root' );
     define( 'DB_PASSWORD', '' ); // or your password
     define( 'DB_HOST', 'localhost' );
     ```

4. **Launch the Website:**
   - Access via browser: `http://localhost/assignment-1-business-landing-page` (or your local domain).

---

## 📸 Submission Files
- Detailed screenshots document included: **`assignment1.rtf`**
