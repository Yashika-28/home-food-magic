<div align="center">

# 🍲 Home Food Magic

### *Connecting Food Lovers with Passionate Home Chefs*

[![Vercel Deployment](https://img.shields.io/badge/Vercel-Deployed-black?style=for-the-badge&logo=vercel)](https://home-food-magic12-obq1y4dvb-woodocarlos-projects.vercel.app/)
[![React Version](https://img.shields.io/badge/React-18.2.0-blue?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![Vite Version](https://img.shields.io/badge/Vite-4.3.9-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.3.2-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![MIT License](https://img.shields.io/github/license/Yashika-28/home-food-magic?style=for-the-badge&color=orange)](LICENSE)

[![GitHub Stars](https://img.shields.io/github/stars/Yashika-28/home-food-magic?style=flat-square&logo=github&color=green)](https://github.com/Yashika-28/home-food-magic/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/Yashika-28/home-food-magic?style=flat-square&logo=github&color=blue)](https://github.com/Yashika-28/home-food-magic/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/Yashika-28/home-food-magic?style=flat-square&logo=github&color=red)](https://github.com/Yashika-28/home-food-magic/issues)

<p align="center">
    <strong>Home Food Magic</strong> is a premium, modern single-page web application that connects food enthusiasts with local home kitchens. It provides a convenient, community-first marketplace where hungry users can buy healthy, authentic, home-cooked food while local chefs can build and run their own digital culinary businesses.
    <br />
    <a href="https://home-food-magic12-obq1y4dvb-woodocarlos-projects.vercel.app/"><strong>Explore the Live App »</strong></a>
</p>

---

</div>

## 📖 Table of Contents
1. [🌟 Key Highlights](#-key-highlights)
2. [🛠️ Tech Stack & Badges](#️-tech-stack--badges)
3. [📁 Folder Hierarchy](#-folder-hierarchy)
4. [⚙️ Installation & Local Setup](#️-installation--local-setup)
5. [🧑‍💻 Core Interfaces & Features](#-core-interfaces--features)
6. [🔮 Roadmap & Future Scope](#-roadmap--future-scope)
7. [🤝 Contribution Guide](#-contribution-guide)
8. [📄 License & Authors](#-license--authors)

---

## 🌟 Key Highlights

* 🍱 **Authentic Cuisines**: Explore dishes ranging from traditional regional delicacies to homemade baked goods.
* ⚡ **Ultra-Fast Performance**: Built on Vite with seamless state routing.
* 🛍️ **Intuitive Customer Workflow**: Seamless shopping cart with sliding panels, custom menu navigation, and reCAPTCHA security.
* 📊 **Full Chef Management Suite**: Interactive chef dashboard to track orders, dish menus, review ratings, and earnings metrics.
* 📝 **Personalized Dining**: Specialized request forms for custom dishes and recurring meal subscriptions (weekly/monthly).

---

## 🛠️ Tech Stack & Badges

### Frontend Stack
* **Framework**: React 18.2 (Context API for State Management)
* **Build System**: Vite (Next-generation build tool)
* **Styling**: Tailwind CSS & CSS Grid (Fully responsive & custom animations)
* **Animations**: Framer Motion (Smooth physics-based transitions)
* **Icons**: Lucide React (Pixel-perfect SVG vectors)
* **Bot Verification**: Google reCAPTCHA v3

### Platform & Deployment
* **Vercel**: Serverless hosting with SPA routing fallbacks configured via `vercel.json`.
* **Git/GitHub**: Code versioning.

---

## 📁 Folder Hierarchy

Below is the directory layout of the application frontend:

```yaml
home-food-magic/
│
├── .gitignore              # Files ignored by Git
├── README.md               # Visual platform overview
│
└── frontend/               # Frontend Project Directory
    ├── public/             # Static Assets (favicons, manifest)
    ├── src/
    │   ├── components/     # UI Components
    │   │   ├── Navbar.jsx               # Header with interactive menus
    │   │   ├── OrderNavBar.jsx          # Contextual navbar for order views
    │   │   ├── Hero.jsx                 # Dynamic landing page intro
    │   │   ├── HowItWorks.jsx           # High-level process steps
    │   │   ├── Testimonials.jsx         # User feedback & review ratings
    │   │   ├── AboutAppDetails.jsx      # Mobile app promo and analytics
    │   │   ├── SignupContact.jsx        # Contact & chef registration forms
    │   │   ├── ChefDashboard.jsx        # Complete management dashboard for home chefs
    │   │   ├── CartPage.jsx             # Sliding shopping cart with total counts
    │   │   ├── PaymentPage.jsx          # Mock payment processing portal
    │   │   ├── CategoryPage.jsx         # Categorized culinary catalogs
    │   │   ├── SubscriptionsPopup.jsx   # Weekly/Monthly meal subscriber form
    │   │   └── PersonalizedRequestPopup.jsx # Custom catering request form
    │   │
    │   ├── App.jsx         # Router configuration & Context Provider
    │   ├── main.jsx        # Root entry point script
    │   └── index.css       # Tailwind configuration imports & custom layout CSS
    │
    ├── package.json        # Dependencies & package configurations
    ├── tailwind.config.js  # Custom tailwind theme styling variables
    ├── postcss.config.js   # CSS compiler options
    └── vite.config.js      # Bundler settings
```

---

## ⚙️ Installation & Local Setup

Get the project running locally in your development workspace:

### Prerequisites
Make sure you have [Node.js (v18 or higher)](https://nodejs.org/) installed on your machine.

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Yashika-28/home-food-magic.git
   cd home-food-magic
   ```

2. **Navigate into the frontend directory:**
   ```bash
   cd frontend
   ```

3. **Install all project dependencies:**
   ```bash
   npm install
   ```

4. **Boot up the Vite development server:**
   ```bash
   npm run dev
   ```
   *The client will boot instantly. Open **[http://localhost:5173](http://localhost:5173)** in your browser.*

5. **Generate a production build:**
   ```bash
   npm run build
   ```
   *Compiles and optimizes your app for production deployment into the `dist/` directory.*

---

## 🧑‍💻 Core Interfaces & Features

### 🛒 The Shopping & Dining Experience
* **Menu Browsing**: Filter meals by chef locations, cuisines, and diets (Veg/Non-Veg).
* **Framer-Motion Cart**: Responsive cart slide-out overlay listing items, item counters, price summaries, and a checkout button.
* **Subscriptions Modal**: Simple choices for users to set up routine meal deliveries.
* **Catering Requests**: Direct custom request submission for bulk/special occasion menu options.

### 📊 Chef Management Hub (`/chef-dashboard`)
An interactive control room for kitchen owners:
* **Analytics Widgets**: Visual tracking of active orders, earnings summaries, and client feedback.
* **Dish Inventories**: Add new custom recipes, edit preparation rates, set vegetarian tags, and toggle instant availability.
* **Order Status Triggers**: Accept order tickets, move them to "Preparing", and dispatch them.

---

## 🔮 Roadmap & Future Scope

- [ ] **Secure OAuth**: Real authentication using Firebase or Auth0.
- [ ] **Payment Gateways**: Integrate Stripe/Razorpay API for live payment verification.
- [ ] **Chef Location Radius**: Geospatial delivery tracking based on Google Maps.
- [ ] **Real-Time Notification Hub**: Web socket-based kitchen-to-doorstep status updates.

---

## 🤝 Contribution Guide

We appreciate contributions to improve **Home Food Magic**!

1. Fork the Project Repository.
2. Create your Feature Branch: `git checkout -b feature/AmazingFeature`
3. Stage & Commit your changes: `git commit -m 'feat: add amazing feature'`
4. Push to your Forked Branch: `git push origin feature/AmazingFeature`
5. Submit a detailed **Pull Request**.

---

## 📄 License & Authors

Distributed under the **MIT License**. See `LICENSE` for more information.

Developed with ❤️ by **[Yashika](https://github.com/Yashika-28)**.
