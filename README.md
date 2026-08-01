# 🍲 Home Food Magic

Home Food Magic is a premium, modern web application designed to connect food lovers with local home chefs. By bridging the gap between hungry users looking for healthy, authentic home-cooked meals and skilled culinary creators, the platform provides a wholesome, community-driven dining experience.

🔗 **Live Deployment:** [home-food-magic12-obq1y4dvb-woodocarlos-projects.vercel.app](https://home-food-magic12-obq1y4dvb-woodocarlos-projects.vercel.app/)

---

## 📌 Project Overview

Home Food Magic delivers a seamless user experience for browsing authentic local kitchens, choosing personalized meal plans, subscribing to daily meals, and managing orders. The application also equips home chefs with an intuitive dashboard to manage their menus, keep track of incoming orders, view earnings, and configure their digital storefront.

---

## 🚀 Key Features

### 👤 For Customers
- **Dynamic Food Discovery**: Browse and search a wide variety of homemade meals categorized by cuisine (e.g., North Indian, South Indian, Desserts, etc.).
- **Interactive Shopping Cart**: Add dishes, customize quantities, and view a breakdown of prices in real-time.
- **Custom Food Requests**: Send personalized dish requests to local chefs using the customized request panel.
- **Meal Subscriptions**: Subscribe to periodic meal plans (weekly/monthly) for convenient, healthy dining.
- **Seamless Checkout**: Access a dedicated mock payment interface for a complete end-to-end checkout simulation.
- **Modern Animations**: Powered by Framer Motion for smooth transitions, slide-out carts, and active hover micro-interactions.

### 👨‍🍳 For Home Chefs (`/chef-dashboard`)
- **Earnings Tracker**: Monitor total revenues, net profit, and orders fulfilled.
- **Dish Management**: Add, edit, or remove menu items with customizable pricing, tags, and availability.
- **Order Management**: Process pending, cooking, and dispatched orders with real-time status updates.
- **Customer Reviews**: View recent feedback left by users for continuous improvement.
- **Storefront Setup**: Profile configuration option tailored for individual home cooks.

---

## 🛠️ Tech Stack

- **Frontend Core**: [React 18](https://react.dev/) & [Vite](https://vitejs.dev/) (For ultra-fast builds and hot module reloading)
- **Routing**: [React Router DOM v7](https://reactrouter.com/) (For single-page-application stateful routing)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) & CSS3 (For highly customizable responsive grid systems)
- **Animations**: [Framer Motion](https://www.framer.com/motion/) (For premium UI slide-ins and modal transitions)
- **Icons**: [Lucide React](https://lucide.dev/) (Clean and consistent SVG iconography)
- **Security**: [React Google reCAPTCHA](https://github.com/dozoisch/react-google-recaptcha) (Bot prevention on login/signup forms)
- **Hosting & Deployment**: [Vercel](https://vercel.com/) (For static-build deployment)

---

## 📂 Project Structure

```
home-food-magic/
│
├── .gitignore               # Ignored files (node_modules, build outputs, environment configs)
├── README.md                # Project documentation
│
└── frontend/                # Frontend codebase
    ├── public/              # Static files (images, logos, favicon)
    ├── src/
    │   ├── components/      # Reusable UI Components
    │   │   ├── Navbar.jsx               # Header navigation & search bar
    │   │   ├── OrderNavBar.jsx          # Specialized navigation bar for ordering dashboard
    │   │   ├── Footer.jsx               # Main footer
    │   │   ├── Hero.jsx                 # Landing page hero banner
    │   │   ├── HowItWorks.jsx           # Guide section explaining the platform
    │   │   ├── Testimonials.jsx         # User success stories and ratings
    │   │   ├── AboutAppDetails.jsx      # Mobile app download promo & statistics
    │   │   ├── SignupContact.jsx        # Contact & chef registration forms
    │   │   ├── ChefDashboard.jsx        # Complete management dashboard for home chefs
    │   │   ├── CartPage.jsx             # Shopping cart slide-over overlay
    │   │   ├── PaymentPage.jsx          # Mock payment processing page
    │   │   ├── CategoryPage.jsx         # Category-specific food browsers
    │   │   ├── SubscriptionsPopup.jsx   # Weekly/Monthly meal subscription modal
    │   │   └── PersonalizedRequestPopup.jsx # Special food request form
    │   │
    │   ├── App.jsx          # Core application router & Cart Context provider
    │   ├── main.jsx         # Application entry point
    │   └── index.css        # Global CSS stylesheet & Tailwind imports
    │
    ├── package.json         # Scripts, configurations, and project dependencies
    ├── tailwind.config.js   # Tailwind theme customized styling tokens
    ├── postcss.config.js    # PostCSS plugins setup
    ├── vite.config.js       # Vite bundler options and configurations
    └── vercel.json          # Deployment routing overrides for Vercel SPA compatibility
```

---

## ⚙️ Installation & Setup

Follow these steps to run the application locally on your computer:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Yashika-28/home-food-magic.git
cd home-food-magic
```

### 2️⃣ Navigate to the Frontend Directory
```bash
cd frontend
```

### 3️⃣ Install Dependencies
```bash
npm install
```

### 4️⃣ Start the Local Development Server
```bash
npm run dev
```

The application will run locally on:
👉 **[http://localhost:5173](http://localhost:5173)**

### 5️⃣ Build for Production
To bundle the application in optimized build files for deployment:
```bash
npm run build
```

---

## 🤝 Contributing

Contributions are always welcome to improve Home Food Magic!
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/NewFeature`)
3. Commit your changes (`git commit -m 'feat: Add some NewFeature'`)
4. Push to the branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👩‍💻 Author

Developed with ❤️ by **Yashika**
