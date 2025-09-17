bus-booking.zip
├─ backend/
│  ├─ package.json
│  └─ server.js
└─ frontend/
   ├─ package.json
   ├─ public/
   │  └─ index.html
   └─ src/
      ├─ index.js
      ├─ App.js
      ├─ index.css
      └─ components/
         ├─ RouteSelector.js
         ├─ BusList.js
         ├─ SeatMap.js
         └─ BookingForm.js
{
  "name": "bus-booking-backend",
  "version": "1.0.0",
  "main": "server.js",
  "scripts": {
    "start": "node server.js",
    "dev": "npx nodemon server.js"
  },
  "dependencies": {
    "body-parser": "^1.20.2",
    "cors": "^2.8.5",
    "express": "^4.18.2"
  },
  "devDependencies": {
    "nodemon": "^2.0.22"
 }
