<h1 align="center"> Personal Portfolio Website (v1)</h1>

<p align="center">
  <strong>A responsive single-page personal portfolio website built with HTML, CSS, JavaScript, and Bootstrap — showcasing skills, projects, resume, and contact information with smooth animations and interactive elements.</strong>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"></a>
  <a href="#"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"></a>
  <a href="#"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"></a>
  <a href="#"><img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"></a>
  <a href="#"><img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"></a>
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-features">Features</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-sections">Sections</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-project-structure">Structure</a> •
  <a href="#-evolution">Evolution</a>
</p>

---

## 📖 Overview

A **responsive single-page personal portfolio website** built with HTML5, CSS3, JavaScript, and Bootstrap. This site served as my personal portfolio and showcases a full range of frontend development skills — responsive layouts, scroll animations, interactive galleries, typing effects, animated counters, and a working PHP-based contact form.

> 📌 **Note:** This is my **previous portfolio** (v1). While I've since built a newer version, I'm keeping this live as a frontend project to demonstrate the skills and techniques I used to build it.

---

## ✨ Features

### 🎨 UI / UX
- **Fully responsive design** — mobile, tablet, and desktop layouts
- **Smooth scroll animations** (AOS library) — sections animate into view
- **Typed text effect** — dynamic role display ("Machine Learning Enthusiast, Cyber Security Enthusiast, Developer...")
- **Animated counters** (PureCounter) — showcase stats with smooth count-up animation
- **Image gallery with lightbox** (GLightbox) — portfolio items open in elegant overlays
- **Portfolio filtering** (Isotope) — filter projects by category
- **Image sliders** (Swiper) — for testimonials and portfolio showcase
- **Custom mobile navigation** — hamburger menu with smooth transitions

### ⚙️ Functionality
- **Working contact form** — PHP backend for email submission
- **Scroll-to-top button** — quick navigation on long scrolls
- **Sticky header** — persistent navigation as you scroll
- **Section-based navigation** — jump to specific sections via menu
- **External social links** — Facebook, Instagram integration

---

## 📑 Sections

The portfolio is organized into a single scrollable page with these sections:

| Section | Purpose |
|---------|---------|
| 🎯 **Hero** | Landing area with name and dynamic typed role animation |
| 👤 **About** | Personal introduction, bio, and key details |
| 📊 **Facts** | Animated counter stats (projects, clients, etc.) |
| 🛠 **Skills** | Technical skill progress bars |
| 💬 **Testimonials** | Quotes and feedback from collaborators |
| 📄 **Resume** | Education, work experience, summary |
| 💼 **Portfolio** | Filterable project showcase with lightbox gallery |
| 🔧 **Services** | Services offered (development, content creation) |
| 📞 **Contact** | Contact form with PHP backend, address, email, phone |

---

## 🛠 Tech Stack

### Core Technologies

| Category | Technology | Purpose |
|----------|-----------|---------|
| **Markup** | HTML5 | Semantic structure |
| **Styling** | CSS3 / SCSS | Custom styles with preprocessor |
| **Interactivity** | JavaScript (Vanilla) | Dynamic behavior |
| **Framework** | Bootstrap 5 | Responsive grid and components |
| **Backend** | PHP | Contact form submission handler |

### Vendor Libraries

| Library | Purpose |
|---------|---------|
| **AOS** | Animate On Scroll effects |
| **Bootstrap** | Responsive UI framework |
| **Bootstrap Icons** | Icon library |
| **BoxIcons** | Additional icon set for social links |
| **GLightbox** | Elegant image/video lightbox galleries |
| **Isotope** | Filterable portfolio grid |
| **PHP Email Form** | PHP form validation and email sending |
| **PureCounter** | Animated number counters |
| **Swiper** | Touch-enabled sliders |
| **Typed.js** | Typewriter/typing animation |
| **Waypoints** | Scroll position triggers |

---

## 🚀 Installation

### Option 1: Open Locally (Static Only)

For the static portion (all sections except contact form):

```bash
# Clone the repository
git clone https://github.com/zishnusarker/PortfolioNew.git
cd PortfolioNew

# Simply open index.html in a browser
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### Option 2: With Live Server (Recommended)

Use a local development server for best experience:

```bash
# Using Python's built-in server
python -m http.server 8000
# Then open http://localhost:8000

# Or use VS Code Live Server extension
# Right-click index.html → "Open with Live Server"
```

### Option 3: Full Deployment (Contact Form Working)

The contact form requires PHP to function. Deploy to any PHP-enabled host:

```bash
# Upload all files to your web host via FTP/cPanel
# Examples: Hostinger, Bluehost, SiteGround, 000webhost (free)

# Configure forms/contact.php with your email:
# $receiving_email_address = 'your-email@example.com';
```

---

## 📁 Project Structure

```
PortfolioNew/
├── index.html                          # Main portfolio page
├── inner-page.html                     # Secondary page template
├── portfolio-details.html              # Individual project detail page
├── Readme.txt                          # Original template readme
├── changelog.txt                       # Template changelog
│
├── forms/                              # Backend form handlers
│   ├── contact.php                     # Contact form processor
│   └── Readme.txt                      # Forms documentation
│
└── assets/
    ├── css/
    │   └── style.css                   # Main stylesheet
    │
    ├── scss/                           # SCSS source files
    │
    ├── js/
    │   └── main.js                     # Custom JavaScript logic
    │
    ├── img/                            # Images (portrait, portfolio, testimonials)
    │
    └── vendor/                         # Third-party libraries
        ├── aos/                        # Scroll animations
        ├── bootstrap/                  # UI framework
        ├── bootstrap-icons/            # Icons
        ├── boxicons/                   # Additional icons
        ├── glightbox/                  # Lightbox gallery
        ├── isotope-layout/             # Portfolio filtering
        ├── php-email-form/             # PHP form validation
        ├── purecounter/                # Counter animations
        ├── swiper/                     # Image sliders
        ├── typed.js/                   # Typing effect
        └── waypoints/                  # Scroll triggers
```

---

## 🎓 Skills Demonstrated

Building this portfolio demonstrated proficiency in:

- ✅ **HTML5 semantic markup** — proper use of `<section>`, `<nav>`, `<header>`, `<footer>`
- ✅ **CSS3 styling** — custom properties, flexbox, grid, media queries
- ✅ **SCSS preprocessing** — variables, nesting, modular styles
- ✅ **Responsive design** — mobile-first approach, breakpoints, fluid layouts
- ✅ **JavaScript DOM manipulation** — event listeners, scroll effects
- ✅ **Third-party library integration** — managing 11+ vendor libraries
- ✅ **Animation & interaction design** — AOS, Typed.js, PureCounter
- ✅ **Form handling** — PHP backend, client-side validation
- ✅ **Cross-browser compatibility** — tested across Chrome, Firefox, Edge, Safari
- ✅ **Performance optimization** — minified assets, lazy loading
- ✅ **Deployment workflow** — FTP uploads, PHP host configuration

---

## 🔄 Evolution

This is **Portfolio v1** — the previous iteration of my personal portfolio. The current version lives in a separate repository:

- 📁 [**Portfolio** (Current)](https://github.com/zishnusarker/Portfolio) — My latest portfolio

This repository is preserved as a **frontend project demonstration** rather than a live portfolio. It captures the techniques and libraries I was using at the time, and serves as a reference for responsive design and multi-library integration.

---

## 🎨 Customization Guide

To adapt this portfolio for your own use:

### 1. Personal Information
Edit `index.html` and update:
- `<title>` with your name
- Hero section with your name and typed roles
- About section with your bio and photo
- Contact details (email, phone, address)

### 2. Portfolio Items
In the `#portfolio` section of `index.html`:
- Replace project images in `assets/img/portfolio/`
- Update project titles, categories, and descriptions
- Modify `data-filter` attributes for category filtering

### 3. Resume Content
Update the `#resume` section with your:
- Education history
- Work experience
- Skills and proficiencies

### 4. Contact Form
Edit `forms/contact.php`:
```php
$receiving_email_address = 'your-email@example.com';
```

### 5. Social Links
Update social media URLs in the header and footer sections.

---

## 🔮 Future Improvements (If Revisiting)

- Migrate to a modern framework (React/Vue/Next.js)
- Add dark mode toggle
- Implement a blog section
- Add multi-language support (i18n)
- Integrate with a CMS for easy content updates
- Add Progressive Web App (PWA) capabilities
- Optimize for Core Web Vitals
- Replace PHP contact form with a serverless solution (Formspree, EmailJS)

---

## 📄 Credits

Built on a Bootstrap template foundation with extensive customization. All personal content, portfolio items, and branding are my own work.

---

## 📧 Contact

- **Email:** zzishnusarker@gmail.com
- **GitHub:** [@zishnusarker](https://github.com/zishnusarker)
- **Current Portfolio:** [Portfolio Repository](https://github.com/zishnusarker/Portfolio)

---

<p align="center">
  Made with ❤️ and lots of HTML, CSS, and JavaScript
</p>

<p align="center">
  <strong>A snapshot of my frontend journey 💻</strong>
</p>
