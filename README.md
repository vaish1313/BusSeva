BusSeva – College Bus Tracking System

BusSeva is a real-time college bus tracking system built using Node.js, Express, and Leaflet.js with OpenStreetMap. It provides live bus location visualization for students and a management dashboard for admins.

Features

- Real-time bus location tracking using Leaflet.js + OpenStreetMap
-  Separate dashboards for Students and Admin
-  Admin can manage routes, buses, and student information
-  Secure route handling 

Tech Stack

- Backend: Node.js, Express.js  
- Frontend: HTML, CSS, JavaScript  
- Maps: OpenStreetMap with Leaflet.js 

Folder Structure

```bash
busseva/
├── controllers/       # Route handlers and logic
├── models/            # MongoDB schemas (Bus, User, etc.)
├── public/            # Static files (CSS, JS, map assets)
├── routes/            # Express.js API/view routes
├── .env               # Environment variables
├── .gitignore         # Ignored files
├── index.js           # Main server entry
├── package.json       # Project metadata
├── package-lock.json  # Dependency lock file
````

Installation

```bash
git clone https://github.com/vaish1313/busseva.git
cd busseva
npm install
npm start
```

What I Learned

* Using Leaflet.js for real-time map rendering
* Modularizing Express apps with MVC structure
* Designing user/admin dashboards for transport systems

Future Improvements

* Live GPS updates via WebSocket or MQTT
* Email/SMS notifications for arrival alerts
* Google login and advanced role-based access
* React-based frontend for better UX
