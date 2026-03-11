# 🌤 Weather App

> **Vibe coded with [Claude.ai](https://claude.ai) — no pain, just vibes.**

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Claude AI](https://img.shields.io/badge/Built%20with-Claude.ai-black?style=for-the-badge)

---

## ✨ What is this?

A clean, minimalist weather app built with pure HTML, CSS, and JavaScript.  
No frameworks. No npm install. No stress. Just open and use. 🚀

---

## 🖼️ Preview

```
🌤 Weather App

[ Select a city ▼ ]  [ Go ]

Chennai, IN
⛅
28°C
partly cloudy

Humidity   Wind    Feels Like
  65%      3.2m/s    30°C
```

---

## 🔥 Features

- 🌍 Dropdown with popular cities (India + World)
- 🌡️ Shows temperature, humidity, wind speed & feels like
- 🎨 Clean minimalist UI — no white box, no clutter
- 🔑 Works in **demo mode** without an API key
- ⚡ Single HTML file — zero dependencies

---

## 🔑 Using a Real API Key (optional)

By default the app runs in **demo mode** with fake data.  
To get live weather:

1. Sign up free at 👉 [openweathermap.org](https://openweathermap.org/api)
2. Copy your API key
3. Open `weather-app.html` and find this line:

```js
const API_KEY = "YOUR_API_KEY_HERE";
```

4. Replace it with your real key:

```js
const API_KEY = "your_actual_key_here";
```

5. Save & refresh. Done! 🌍

> ⚠️ New API keys take ~15 minutes to activate after signup.

---

## 🗂️ Project Structure

```
weather-app/
└── weather-app.html   ← everything is here (HTML + CSS + JS)
```

Yep. One file. That's the whole project. 😎

---

## 🤖 How it was built

This entire app was **vibe coded using [Claude.ai](https://claude.ai)**.

No prior frontend experience needed. Just described what I wanted in plain English and Claude wrote the code, explained every line, and fixed bugs in real time — step by step, like pair programming with an AI.

**The conversation flow:**
- 💬 *"Build a minimalist weather app"* → got the base app
- 💬 *"Remove the outer white box"* → cleaner UI
- 💬 *"Make cities in a dropdown"* → replaced input with select
- 💬 *"Dropdown is not showing up properly"* → fixed the arrow styling
- 💬 *"Write a README for GitHub"* → you're reading it 😄

---

## 📚 What I Learned

- How HTML, CSS, and JS work together in a single file
- How to use a public API with a key
- How `fetch()` works to get data from the internet
- How CSS `appearance: none` customizes dropdowns
- How to read and understand code written by AI

---

## 🛠️ Built With

| Tool | Purpose |
|------|---------|
| HTML | Structure |
| CSS | Styling |
| JavaScript | Logic & API calls |
| [OpenWeatherMap API](https://openweathermap.org/api) | Weather data |
| [Claude.ai](https://claude.ai) | Vibe coding partner 🤖 |

---

<p align="center">Made with ☁️ and vibes &nbsp;|&nbsp; Powered by <a href="https://claude.ai">Claude.ai</a></p>
