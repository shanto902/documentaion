# Influencer Frontend

![Influencer Frontend](https://img.shields.io/badge/React-16.14.0-blue.svg) ![Vite](https://img.shields.io/badge/Vite-Fast%20Build-orange.svg) ![Semantic UI](https://img.shields.io/badge/UI-Semantic%20UI%20React-green.svg) ![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

## 🚀 Overview

The **Influencer Frontend** is a web application designed to provide influencer-related functionalities with a seamless and responsive user experience. Built using **React** and powered by **Vite**, this project ensures high performance, efficient data fetching, and a smooth UI. The project incorporates third-party services for analytics, authentication, and real-time updates.

## 🛠 Tech Stack

- **Framework:** React (16.14.0)
- **Bundler:** Vite (Optimized build process for faster development)
- **Styling:** SCSS & Semantic UI React (Custom styles with pre-designed UI components)
- **State Management:** React Query (Efficient caching and API data synchronization)
- **API Handling:** Axios (Simplifies API requests with automatic transformations and error handling)
- **Performance Optimization:** Partytown (Offloads third-party scripts to improve page load speed)
- **Real-time Communication:** Pusher.js & Socket.io Client (Used for live updates and notifications)

## ✨ Features

### 📊 Influencer Dashboard

- Displays key metrics and insights
- Provides an intuitive interface for managing content and interactions

### 🔐 Authentication System

- Supports social logins with **Google** and **Facebook**
- Secure session handling with **Universal Cookie**

### 📝 Content Management

- Create, edit, and publish posts effortlessly
- Includes emoji support with **emoji-picker-react**

### 📡 Real-time Updates

- Uses WebSockets for live notifications and messages

### ⚡ Lazy Loading & Performance Enhancements

- Implements **react-lazyload** for images and content
- Uses **Partytown** to optimize script handling for third-party services

### 🚀 SEO Optimization

- Uses **semantic HTML** and metadata for better search engine rankings
- Implements Google Analytics with **react-ga4**

## 📂 Codebase Structure

```
📦 influencer_frontend
├── 📂 public              # Static assets
├── 📂 src                 # Source code
│   ├── 📂 components      # Reusable UI components
│   ├── 📂 context         # Global state and providers
│   ├── 📂 HOC             # Higher Order Components
│   ├── 📂 hooks           # Custom React hooks
│   ├── 📂 layout          # Layout components
│   ├── 📂 lib             # External libraries and API wrappers
│   ├── 📂 pages           # Page-level components
│   ├── 📂 svg_icons       # SVG icons used across the project
│   ├── 📂 utils           # Helper functions and utilities
│   ├── _mixins.scss       # SCSS mixins for styling
│   ├── App.jsx            # Root component
│   ├── authenticate.js    # Authentication logic
│   ├── index.jsx          # Entry point
│   ├── serviceWorker.js   # Service worker for PWA
│   ├── variable.scss      # Global SCSS variables
│   ├── vite-env.d.ts      # TypeScript environment file for Vite
└── 📜 package.json        # Project dependencies and scripts
```

## 📦 Dependencies

### Main Dependencies:

- **@builder.io/partytown** (Optimized script handling)
- **@fingerprintjs/fingerprintjs** (User fingerprinting)
- **@giphy/js-fetch-api & @giphy/react-components** (GIF integration)
- **@react-pdf/renderer** (PDF generation)
- **Axios** (API requests)
- **Date-fns & Moment.js** (Date handling)
- **Framer Motion** (Animations)
- **Pusher.js & Socket.io Client** (Real-time communication)
- **React Query** (Efficient data fetching)
- **Recharts** (Data visualization)
- **Semantic UI React** (UI components)
- **Universal Cookie** (Authentication handling)

### Development Dependencies:

- **@vitejs/plugin-react-refresh** (React fast refresh for Vite)
- **Sass** (SCSS support)
- **Vite** (Fast bundling and development server)
- **Webpack Bundle Analyzer** (Bundle size optimization)

## 🏗 Installation & Setup

### Prerequisites

Ensure you have **Node.js** and **Git** installed on your system.

1. **Clone the repository:**

   ```sh
   git clone <repository-url>
   cd influencer_frontend
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

   or using Bun:

   ```sh
   bun install
   ```

3. **Environment Configuration:**

   - All meta files, including API base URLs, are defined in `utils/consts.js`.
   - There is no need to specify `.env` manually.

4. **Run the development server:**

   ```sh
   npm run dev
   ```

   or with Bun:

   ```sh
   bun dev
   ```

5. **Build for production:**
   ```sh
   npm run build
   ```
   The output will be in the `dist/` folder, ready for deployment.

## 📖 Usage

- Navigate to the **dashboard** to access influencer-specific features.
- Connect your **social accounts** for authentication and analytics.
- Manage and track **real-time engagement data**.
- Ensure **backend API endpoints** are correctly configured before making requests.

## 📌 Additional Notes

- **Partytown** is used to offload third-party scripts for improved performance.
- **React Query** handles efficient API fetching and state synchronization.
- **React Slick** is integrated for a smooth carousel experience.
- **React Date Range** is used for filtering data within specific time periods.
- **Universal Cookie** helps manage authentication and session data across the application.
