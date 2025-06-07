# Practical 2 Reflection: RESTful Weather App ☁️🌦️

## 📌 What I Built

A weather app using plain **HTML/CSS/JS** that demonstrates all 4 major REST API methods:
- `GET`: Fetch weather info from **OpenWeatherMap**
- `POST`: Save favorite locations with custom notes
- `PUT`: Edit saved location details
- `DELETE`: Remove unwanted locations

Also used **LocalStorage** to manage user data without a backend.

---

## 🔍 Key Features

✅ **Get Weather**  
Enter a city name → Fetch live weather (temp, humidity, wind)

✅ **Save Location**  
POST your favorite cities with custom name & country

✅ **Edit Location**  
PUT method to update city details

✅ **Delete Location**  
Click delete to remove a saved place

✅ **Clean UI**  
Simple, mobile-friendly design with:
- Loading indicators
- Error messages
- Empty field warnings

---

## ⚙️ Setup Steps

1. Create a folder and add:
   - `index.html`
   - `script.js`

2. Get API Key from [OpenWeatherMap](https://openweathermap.org/api)

3. Paste your API key in `script.js`:
```js
const API_KEY = 'YOUR_OPENWEATHERMAP_API_KEY';
💻 Technologies Used
HTML/CSS/JavaScript

OpenWeatherMap API (GET)

JSONPlaceholder API (POST/PUT/DELETE simulation)

LocalStorage for storing user data

🧠 What I Learned
How REST APIs work in real-world apps

Using fetch() for GET, POST, PUT, DELETE in JS

Handling API responses and errors

Creating interactive, responsive web apps without frameworks

Managing client-side data using LocalStorage

🔗 Useful Links
🌐 OpenWeatherMap API

🧪 JSONPlaceholder API

