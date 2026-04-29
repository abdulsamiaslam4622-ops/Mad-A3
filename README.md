

All App's Google Link : https://drive.google.com/drive/folders/1KXCIe8kgXCpbOs2PMi4sW5HrUOXAujwE?usp=sharing


<img width="433" height="482" alt="image" src="https://github.com/user-attachments/assets/3a413f3f-c3e8-40a5-b0fd-e56e2bbf9a51" />


https://github.com/abdulsamiaslam4622-ops/Mad-A2/blob/main/README.md

# IshratFits - Premium E-Commerce App

IshratFits is a state-of-the-art mobile e-commerce platform built with **React Native (Expo SDK 55)** and a robust **Node.js/Express** backend. Designed for a premium shopping experience, it features a sleek dark mode, vibrant aesthetics, and high-performance data handling.

<img width="892" height="886" alt="image" src="https://github.com/user-attachments/assets/bc5bf0da-e84d-4d44-8aee-d713f35a3f13" />



Click on link to Download the App: https://expo.dev/artifacts/eas/way5AfWy8P8Xzu2AU2ZNPJ.apk

Click on QR to donwload the App: <img width="181" height="181" alt="image" src="https://github.com/user-attachments/assets/83966a50-df94-48d4-acb5-4a94c79f0a03" />

## ✨ Features

- **🛍️ Seamless Shopping**: Browse, search, and filter through a diverse collection of premium products.
- **🌙 Elegant Dark Mode**: A visually stunning interface designed for modern aesthetics and reduced eye strain.
- **🚀 Real-time Updates**: Instant feedback and live data synchronization between frontend and backend.
- **💳 Secure Checkout**: Integrated flow for managing cart and processing orders.
- **📱 Cross-Platform**: Optimized for both iOS and Android using Expo.

## 🛠️ Tech Stack

### Frontend
- **Framework**: [React Native (Expo SDK 55)](https://expo.dev/)
- **Navigation**: [React Navigation 6](https://reactnavigation.org/)
- **State/Networking**: [Axios](https://axios-http.com/)
- **UI Components**: Custom Vanilla CSS-in-JS for maximum performance and flexibility.

### Backend
- **Environment**: [Node.js](https://nodejs.org/)
- **Framework**: [Express.js](https://expressjs.com/)
- **Database**: [MySQL](https://www.mysql.com/) (via `mysql2`)
- **Middleware**: [CORS](https://www.npmjs.com/package/cors), [Dotenv](https://www.npmjs.com/package/dotenv)

## 📂 Project Structure

```text
E-com-app/
├── frontend/           # Expo React Native mobile application
│   ├── src/
│   │   ├── components/ # Reusable UI components
│   │   ├── screens/    # App screens (Home, Product, Cart, Profile)
│   │   └── services/   # API communication (Axios)
│   └── App.js          # Main entry point
├── backend/            # Express.js REST API
│   ├── config/         # Database and env configurations
│   ├── controllers/    # Business logic
│   ├── routes/         # API endpoints
│   └── server.js       # Main server entry point
└── db/                 # Database scripts and schemas
```

## 🚀 Getting Started

### 1. Prerequisites
- **Node.js** (v18 or later)
- **npm** or **yarn**
- **MySQL** instance running locally or on a server

### 2. Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables in a `.env` file (see `backend/config` for reference).
4. Start the server:
   ```bash
   npm start
   ```

### 3. Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the Expo development server:
   ```bash
   npx expo start
   ```
4. Use **Expo Go** to scan the QR code and run the app on your mobile device.

## 📄 License
This project is licensed under the ISC License.

---
*Built with ❤️ by IshratFits Team*


<img width="1188" height="1324" alt="ChatGPT Image Apr 29, 2026, 04_10_09 AM" src="https://github.com/user-attachments/assets/e899ab6e-20b9-4b81-8e71-de36dc3a41c1" />

# 💳 Expense Tracker Pro

<img width="886" height="886" alt="image" src="https://github.com/user-attachments/assets/6648fc27-b525-4cfb-84f7-8353d8870ba0" />


## 🚀 Overview
**Expense Tracker Pro** is a high-performance, premium financial management application. Built with a sleek dark-mode aesthetic and powered by modern web technologies, it allows users to track their income and expenses with ease, featuring 3D visualizations and local-first data persistence.

---

## ✨ Key Features
- **📊 Real-time Dashboard**: Visualize your spending habits with interactive 3D charts.
- **🌑 Premium Dark Mode**: A state-of-the-art UI designed for visual comfort and elegance.
- **📱 Cross-Platform**: Built with Expo/React Native for a seamless experience on iOS, Android, and Web.
- **⚡ Fast Persistence**: Uses SQLite for local storage and an Express/MySQL backend for data synchronization.
- **📈 Detailed Analytics**: Categorize transactions and monitor monthly trends.

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: [React Native](https://reactnative.dev/) with [Expo](https://expo.dev/)
- **Visuals**: [Three.js](https://threejs.org/) & [React Three Fiber](https://docs.pmnd.rs/react-three-fiber/) for 3D data visualization.
- **Database**: [Expo SQLite](https://docs.expo.dev/versions/latest/sdk/sqlite/) for lightning-fast local storage.
- **Styling**: Native styling with a focus on dark-mode aesthetics.

### Backend
- **Runtime**: [Node.js](https://nodejs.org/)
- **Framework**: [Express.js](https://expressjs.com/)
- **Database**: [MySQL](https://www.mysql.com/) (mysql2 driver)
- **Middleware**: CORS, Dotenv for environment management.

---

## 📂 Project Structure
```text
expense-tracker-pro/
├── frontend/          # React Native / Expo Application
│   ├── src/           # Component logic and screens
│   ├── assets/        # Static images and icons
│   └── App.js         # Entry point
├── backend/           # Node.js / Express API
│   ├── src/           # API routes and controllers
│   ├── schema.sql     # Database initialization script
│   └── server.js      # Server entry point
└── README.md          # Project documentation
```

---

## ⚙️ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Expo Go](https://expo.dev/go) app (for mobile testing)

### Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd expense-tracker-pro
   ```

2. **Setup the Backend**:
   ```bash
   cd backend
   npm install
   # Configure your .env file with MySQL credentials
   npm start
   ```

3. **Setup the Frontend**:
   ```bash
   cd ../frontend
   npm install
   npx expo start
   ```

---

## 🗄️ Database Setup
The backend requires a MySQL database. You can initialize the schema using the provided script:
```bash
mysql -u your_user -p < backend/schema.sql
```

---

## 🎨 Design Philosophy
The app follows a "Pro" design language, prioritizing high contrast, neon accents (Blue & Violet), and fluid animations to make financial tracking not just useful, but enjoyable.

---

## 📄 License
This project is licensed under the MIT License.


<img width="768" height="849" alt="task3_feed_app" src="https://github.com/user-attachments/assets/a3d01ecd-8889-4ff4-92bf-69f6ac16a069" />



# Feed App - Team NIXH

A modern, high-performance social feed application built with **React Native (Expo SDK 55)** and a **Node.js/Express** backend. This project features a premium UI design with Glassmorphism effects and seamless data synchronization.


<img width="870" height="872" alt="image" src="https://github.com/user-attachments/assets/eff3532b-1e28-4894-825d-c63785dee007" />


## 📱 Features

- **Dynamic Feed**: Browse posts with smooth scrolling and vibrant visual aesthetics.
- **Glassmorphism UI**: Premium frosted-glass effects using `expo-blur` and `expo-linear-gradient`.
- **Post Details**: Detailed view for individual posts with high-quality layouts.
- **Create Content**: Interface for users to publish new posts to the feed.
- **User Profiles**: Personalized profile screens with modern typography.
- **Cross-Platform**: Fully compatible with iOS, Android, and Web.

## 🛠️ Tech Stack

### Frontend
- **Framework**: React Native (Expo SDK 55)
- **Navigation**: React Navigation 7
- **Styling**: Vanilla CSS-in-JS with `expo-linear-gradient` and `expo-blur`
- **Icons**: Lucide React Native
- **Networking**: Axios

### Backend
- **Environment**: Node.js
- **Framework**: Express.js
- **Database**: MySQL (supported via `mysql2`)
- **Middleware**: CORS, JSON Parsing

## 📂 Project Structure

```text
feed-app/
├── frontend/           # Expo React Native mobile application
│   ├── src/
│   │   ├── components/ # Reusable UI components
│   │   ├── screens/    # App screens (Feed, Details, Create, Profile)
│   │   ├── navigation/ # App routing configuration
│   │   └── services/   # API communication logic
│   └── App.js          # Entry point
└── backend/            # Node.js Express server
    ├── server.js       # Main server file
    └── docs/           # Backend documentation
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or later recommended)
- npm or yarn
- Expo Go app on your mobile device (to test the frontend)

### 1. Setup Backend
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npm start
   ```
   *The server will run at `http://localhost:3000`.*

### 2. Setup Frontend
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the Expo development server:
   ```bash
   npx expo start
   ```
4. Scan the QR code with your **Expo Go** app (Android) or **Camera** app (iOS).

## ⚙️ Configuration

### Connecting Frontend to Backend
To connect your mobile device to the local backend server, ensure both devices are on the same Wi-Fi network. Update the `BASE_URL` in `frontend/src/services/api.js` to your computer's local IP address:

```javascript
// frontend/src/services/api.js
const BASE_URL = 'http://YOUR_LOCAL_IP:3000';
```

## 📄 License
This project is licensed under the ISC License.

<img width="3840" height="4320" alt="task4_food_delivery_app_4K" src="https://github.com/user-attachments/assets/b11f78f1-2bd8-45bd-9442-0d18fe819214" />
---

# 🚀 Foreign Delivers - Premium Food Delivery App

Foreign Delivers is a full-stack, high-performance food delivery application designed to provide a seamless ordering experience. Built with **Expo (React Native)** for the frontend, **Node.js (Express)** for the backend, and **MySQL** for robust data management.


<img width="860" height="863" alt="image" src="https://github.com/user-attachments/assets/0c4b36e1-be7b-4a45-b204-93272c060c0a" />


## ✨ Key Features

- **Intuitive UI/UX**: Sleek dark mode design with vibrant accents for a premium feel.
- **Fast Search & Filtering**: Find your favorite cuisines (Pizza, Sushi, Burgers) instantly.
- **Real-time Order Tracking**: Stay updated on your meal's journey.
- **Restaurant Management**: Seamlessly integrated backend for managing menus and orders.
- **Secure Authentication**: Robust user data protection.

## 🛠️ Tech Stack

- **Frontend**: React Native, Expo, Axios
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Environment**: Dotenv for secure configuration

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+)
- [Expo Go](https://expo.dev/client) app on your mobile device (for testing)
- MySQL Server

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/food-delivery-app.git
cd food-delivery-app
```

### 2. Backend Setup
```bash
cd backend
npm install
# Create a .env file and add your DB credentials
npm start
```

### 3. Frontend Setup
```bash
cd ../frontend
npm install
npx expo start
```

## 📂 Project Structure

- `frontend/`: Expo React Native application.
- `backend/`: Express.js server and API endpoints.
- `db/`: Database schemas and migration scripts.
- `assets/`: UI assets and design mockups.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
Developed with ❤️ by the Foreign Delivers Team.

Click on this Link to Install the App: https://expo.dev/accounts/sami9201/projects/foreign-delivers/builds/b5a67165-c254-4ffc-b734-fde26474f3b9


<img width="3840" height="4320" alt="task5_moviehub_4K (1)" src="https://github.com/user-attachments/assets/75bf3b82-9ae1-4521-b307-def89652ea69" />

# 🎬 MovieHub - Premium Movie Booking Experience

MovieHub is a sophisticated, full-stack movie booking application designed for a seamless cinematic experience. Built with a robust Node.js/MySQL backend and a sleek React Native (Expo) frontend, it allows users to browse current blockbusters, select their preferred seats, and book tickets in real-time.

<img width="887" height="718" alt="image" src="https://github.com/user-attachments/assets/5f73e7f8-0477-4da7-b508-7ae1a84b4175" />


## ✨ Features

- **Dynamic Movie Catalog**: Browse movies with detailed metadata including genre, price, and high-quality posters.
- **Interactive Seat Selection**: Real-time seat status tracking (Available/Booked).
- **Seamless Booking**: Integrated booking flow with backend confirmation.
- **Admin Utilities**: Ability to reset all seats for system maintenance.
- **Cross-Platform**: Mobile-first design optimized for Android and iOS via Expo.

## 🛠️ Tech Stack

### Frontend
- **Framework**: React Native / Expo
- **Navigation**: React Navigation (Stack)
- **Styling**: Native Base / Custom CSS-in-JS
- **API Client**: Axios

### Backend
- **Server**: Node.js / Express
- **Database**: MySQL (hosted on MySQL Workbench)
- **CORS**: Configured for mobile APK access

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- MySQL Server
- Expo Go (for mobile testing)

### 1. Database Setup
1. Open your MySQL client.
2. Execute the schema found in `db/schema.sql` to create the `MovieHub` database and required tables.
3. Update the credentials in `backend/server.js`:
   ```javascript
   const db = mysql.createConnection({
     host: '127.0.0.1',
     user: 'root',
     password: 'your_password',
     database: 'MovieHub'
   });
   ```

### 2. Backend Installation
```bash
cd backend
npm install
npm start
```
The server will run at `http://localhost:3000`.

### 3. Frontend Installation
```bash
cd frontend
npm install
npx expo start
```
Scan the QR code with your **Expo Go** app to view the application.

## 📱 Mobile Access (APK)
To ensure the application connects to the backend when running as an APK:
- The backend is configured to listen on `0.0.0.0`.
- Ensure your mobile device and server are on the same Wi-Fi network.
- Update the `IP_ADDRESS` in `backend/server.js` to your machine's local IP.

---

Built with ❤️ by [Your Name/Team]


To download Click on this link : https://expo.dev/artifacts/eas/tvfCPBQwYpRBLGKRS7jcPe.apk

Scan QR to dwonload App: <img width="182" height="180" alt="image" src="https://github.com/user-attachments/assets/c4ed6659-7afb-486f-ac2d-011cccb535ef" />






