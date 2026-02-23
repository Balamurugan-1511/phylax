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
* **Styling:** Custom CSS

---

## ⚡ Installation

```bash
# Clone repo
git clone https://github.com/<your-username>/phylax.git

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

* Backend integration (Node / Flask)
* OAuth authentication
* Weather API integration
* Database for zones & users
* Real-time updates (Socket)
* Notification alerts

---

## 📜 License

ISC
