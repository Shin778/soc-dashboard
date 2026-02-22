# 🛡️ SOC Threat Intelligence Dashboard

> A responsive, real-time Security Operations Center (SOC) simulation interface developed as a Master's degree final project.

## 📖 About The Project
This project is a frontend simulation of a Cybersecurity Operations Center. It visualizes network traffic, active incidents, and potential threats (such as DDoS attacks, SQL Injections, and MITM) in real-time. The application is designed to demonstrate how security analysts monitor and respond to critical system alerts.

## 👨‍💻 My Role & Contributions
This was a collaborative team project. My primary responsibility was the **Frontend UI/UX Architecture**, while the **Client-Side Logic** was a shared effort between me and my teammate, Nijat Najafov.

* **Shared State & Logic Management:** Collaborated on building the React logic using **Hooks (useState, useEffect)**. While Nijat architected the core data simulation hooks and interval logic, I focused on managing the local UI state for interactive components (e.g., live feed toggling, incident selection, and conditional styling).
* **Navigation Architecture:** Engineered seamless client-side routing across 7 specific threat simulation pages using **React Router**, ensuring a smooth Single Page Application (SPA) experience.
* **UI Development:** Designed and built a fully responsive, dark-themed dashboard using **Tailwind CSS**, utilizing advanced CSS Grid and Flexbox layouts for optimal data presentation.
* **Data Visualization:** Integrated **Recharts** to render complex, real-time area charts for inbound/outbound network traffic and threat detection.
* **Interactive Elements:** Utilized **Framer Motion** for smooth component transitions and alert animations, significantly improving the user experience.

## ✨ Key Features
* 🔴 **Live Threat Feed:** Real-time generation of simulated cybersecurity threats with severity-based conditional styling.
* 📊 **Interactive Analytics:** Dynamic area charts showing network bandwidth and active threats.
* 🚦 **System Status Widgets:** Monitoring modules for server health, firewall status, and network latency.
* 📱 **Fully Responsive:** Pixel-perfect layout that adapts to any screen size.

## 🛠️ Tech Stack
* **Core:** React.js (Hooks, Functional Components)
* **Styling:** Tailwind CSS, CSS Grid/Flexbox
* **Routing:** React Router v7
* **Visualization & Animation:** Recharts, Framer Motion, Lucide React (Icons)

## 🚀 Getting Started

To run this project locally:

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/soc-dashboard.git](https://github.com/your-username/soc-dashboard.git)
   ```
2. Navigate to the project directory:
   ```bash
   cd soc-dashboard
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
The app will be available at [http://localhost:3000](http://localhost:3000).

## 👥 Team
This project was successfully developed by master's students at Azerbaijan Technical University:
* **Huseynli Murad** (Frontend UI/UX, Visualization & UI State Logic)
* **Nijat Najafov** (Backend Simulation & Core Data Streams)
* **Elmin Nuriyev** (Project Architecture Support)
