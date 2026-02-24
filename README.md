Here is the corrected and properly formatted `README.md` file. The main issues with the previous version were inconsistent indentation (using spaces vs. code block ticks) in the "Project Structure" section.

```markdown
# 💻 M. Puneet Janakiram | Portfolio

![React](https://img.shields.io/badge/React-19.1.0-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-6.3.5-646CFF?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.1.8-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

> A modern, responsive personal portfolio website built with React, Vite, and Tailwind CSS to showcase my projects, skills, and professional journey.

![Portfolio Preview](https://via.placeholder.com/1200x600/0f172a/FFFFFF?text=Portfolio+Preview+Image)

---

## 📋 Table of Contents
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started](#-getting-started)
- [📁 Project Structure](#-project-structure)
- [📬 Contact](#-contact)

---

## ✨ Features

- **Animated Welcome Loader**: A smooth, typewriter-style loading screen to welcome visitors.
- **Modern UI/UX**: Sleek design with glassmorphism effects, gradient backgrounds, and smooth transitions.
- **Responsive Design**: Fully optimized for all devices, from mobile phones to desktop screens.
- **Interactive Project Gallery**: Dynamic cards with expandable details, technology tags, and direct links.
- **About Me Section**: Comprehensive overview of education, core competencies, and technical skills.
- **Functional Contact Form**: Email integration powered by EmailJS to send messages directly.
- **Smooth Animations**: Implemented using Framer Motion and custom CSS animations for a fluid experience.

---

## 🛠️ Tech Stack

| Category        | Technologies                                                                 |
|-----------------|------------------------------------------------------------------------------|
| **Frontend**    | ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react) ![Vite](https://img.shields.io/badge/Vite-20232A?style=flat&logo=vite) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-20232A?style=flat&logo=tailwind-css) |
| **Animation**   | ![Framer Motion](https://img.shields.io/badge/Framer_Motion-20232A?style=flat&logo=framer) |
| **Routing**     | ![React Router](https://img.shields.io/badge/React_Router-20232A?style=flat&logo=react-router) |
| **Email Service** | ![EmailJS](https://img.shields.io/badge/EmailJS-20232A?style=flat&logo=mailchimp) |
| **Deployment**  | ![Vercel](https://img.shields.io/badge/Vercel-20232A?style=flat&logo=vercel) ![Netlify](https://img.shields.io/badge/Netlify-20232A?style=flat&logo=netlify) |

---

## 🚀 Getting Started

Follow these instructions to set up the project locally.

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/puneet-jr/PORTFOLIO.git
   cd MY-Portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up Environment Variables**

   Create a `.env` file in the root directory and add your [EmailJS](https://www.emailjs.com/) credentials:
   ```env
   VITE_SERVICE_ID=your_service_id
   VITE_TEMPLATE_ID=your_template_id
   VITE_PUBLIC_KEY=your_public_key
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

---

## 📁 Project Structure

```
MY-Portfolio/
├── src/
│   ├── components/
│   │   ├── Navbar.jsx          # Navigation bar with scroll effects
│   │   ├── MobileMenu.jsx      # Responsive hamburger menu
│   │   ├── LoadingScreen.jsx   # Initial loading animation
│   │   └── sections/
│   │       ├── Home.jsx        # Landing page / Hero section
│   │       ├── About.jsx       # Education & Skills section
│   │       ├── Projects.jsx    # Project showcase grid
│   │       ├── Contact.jsx     # Contact form & details
│   │       └── RevealOnScroll.jsx # Scroll animation wrapper
│   ├── App.jsx                 # Main application component
│   ├── main.jsx                # Entry point
│   └── index.css               # Global styles & Tailwind config
├── index.html
├── package.json
└── vite.config.js
```

---

## 📬 Contact

**M. Puneet Janakiram**

- 📧 Email: [puneetjanakiram@gmail.com](mailto:puneetjanakiram@gmail.com)
- 🐙 GitHub: [puneet-jr](https://github.com/puneet-jr)

---

> Built with ❤️ by **Puneet Janakiram**
```
