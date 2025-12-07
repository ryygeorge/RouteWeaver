# 🧭 RouteWeaver — Intelligent Trip Planning System

RouteWeaver is a smart, scalable, and user-friendly itinerary planning application designed to simplify road-trip planning.  
It enables users to create optimized routes, explore curated travel packages, and receive personalized suggestions — all within a clean and intuitive interface.

---

## 🚀 Overview

RouteWeaver enhances modern travel planning through automation and personalization.  
With RouteWeaver, users can:

- Build and save **custom travel routes**
- Explore **ready-made travel packages**
- Get **AI-driven recommendations** based on interests and keywords
- Use **SmartVacay**, an intelligent feature that analyzes personal calendars to suggest ideal travel dates

---

## 🧩 Key Features

- **Custom Route Creator:** Generate optimized travel routes using Google Maps data  
- **SmartVacay (AI-Assisted):** Suggests travel windows by reading work or personal calendars  
- **Dynamic Suggestions:** Filter and discover destinations based on interests like nature, food, adventure, etc.  
- **Saved Trips:** View, manage, and update previously created routes  
- **Travel Packages:** Choose from pre-built optimized travel plans  
- **Secure Authentication:** Login and user data handled with Node.js + MongoDB  

---

## 🛠️ Tech Stack

- **Frontend:** React.js (Vite)  
- **Backend:** Node.js + Express.js  
- **Database:** MongoDB  
- **APIs:** Google Maps API, OSRM API, Gemini API, Google Calendar API  

---

## 🖼️ Application Screens

### 🏠 Home Page  
Minimal and welcoming interface for users.  
![Home Page](images/home.jpg)

---

### 🔐 Login / Signup  
Secure user login and account creation.  
![Login Page](images/login.jpg)

---

### 🗺️ Query Page  
Generate routes based on travel preferences and destinations.  
![Query Page](images/querypage.jpg)

---

### 💾 Saved Routes  
Access and manage your previously created routes.  
![Saved Routes](images/savedroutes.jpg)

---

### 🌴 SmartVacay  
AI-driven vacation planner synced with your calendar.  
![SmartVacay](images/smartvacay.jpg)

---

### 💡 Suggestions Page  
Get personalized place suggestions based on interest keywords.  
![Suggestions Page](images/suggestion.jpg)

---

### ✈️ Travel Packages  
Browse optimized travel packages near your current location.  
![Travel Packages](images/travelpackages.jpg)

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/ryygeorge/Project_RouteWeaver

# Start backend services
cd Backend
npm install
npm start

# Navigate to the frontend directory
cd RouteWeaver

# Install frontend dependencies
npm install

# Run development server
npm run dev
