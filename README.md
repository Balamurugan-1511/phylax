# Phylax

**AI-Driven Geography-Aware Disaster Risk Prediction & Relief Coordination System**

A modern web platform that predicts disaster risk based on location and weather data while enabling real-time coordination of relief efforts.

---

## 🚀 Features

### 🔐 Authentication

* Google / Facebook / Email login
* Secure session management

### 📊 Dashboard

* Real-time weather insights (rainfall, temperature, humidity)
* AI-based disaster risk prediction
* Visual risk meter showing threat levels
* Active emergency zones overview

### ⚠️ Risk Prediction

* Uses location + weather patterns
* Displays risk levels:

  * Evacuate Immediately
  * Most Expected
  * Expected
  * Likely
  * Unlikely

### 📍 Zone Management

**Create Zone**

* Auto location detection
* Emergency type & severity selection
* Visible to nearby users
* Becomes active when multiple users join

**Join Zone**

* Join via link or search nearby zones
* View distance & member count

**Zone Coordination**

* See affected people & needs
* Offer help (Food, Water, Medical, Transport, Volunteer, Financial)

---

## 🛠 Tech Stack

* **Frontend:** React + Vite
* **Routing:** React Router
* **Icons:** Lucide React
* **Backend:** Node.js + Express
* **Database:** MongoDB
* **Styling:** Custom CSS

---

## 💾 Database (MongoDB)

The platform uses **MongoDB** to store:

* User accounts & authentication data
* Emergency zones
* Zone members & affected people
* Help requests (food, water, medical, etc.)
* Disaster prediction logs

---

## ⚡ Installation

```bash
# Clone repo
git clone https://github.com/Balamurugan-1511/phylax

# Go to project folder
cd phylax

# Install dependencies
npm install

# Run project
npm run dev
```

---

## 📂 Project Structure

```
src/
 ├── pages/
 ├── styles/
 ├── App.jsx
 ├── main.jsx
 └── index.css
```

---

## 🔄 User Flow

Login → Dashboard → Predict Risk → Create/Join Zone → Coordinate Help

---

## 🔮 Future Improvements

* Real-time updates
* Push notifications for alerts
* ML prediction model
* Mobile app integration

---


