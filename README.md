# 🌄 Personal Dashboard — Chrome Extension

A Chrome extension that transforms your browser's new tab page into a beautiful personal dashboard. Each new tab displays a stunning nature background, the current time, live weather based on your location, and the latest Dogecoin market data.

Built as a project to practice asynchronous JavaScript, working with APIs, and Chrome Extension development.

---

## ✨ Features

- 🌅 Displays a random nature background on every new tab
- 📸 Shows the photographer's name for each background image
- 🕒 Displays the current time and updates every second
- 📍 Detects your location to display current weather
- 🌡️ Shows current temperature and city
- 🪙 Displays live Dogecoin price information, including:
  - Current price
  - 24-hour high
  - 24-hour low
- ⚡ Replaces Chrome's default New Tab page

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript
- Chrome Extensions (Manifest V3)

---

## 🔌 APIs Used

- **Unsplash API** – Random nature backgrounds
- **OpenWeather API** – Current weather based on geolocation
- **CoinGecko API** – Live cryptocurrency market data

> **Note:** This project accesses the APIs through Scrimba proxy endpoints where applicable.

---

## 📂 Project Structure

```plaintext
personal-dashboard/
│
├── icon.png
├── index.css
├── index.html
├── index.js
├── manifest.json
├── package.json
├── README.md
└── vite.config.js
```

---

## 🚀 Installation

Since this is a Chrome extension, install it manually:

1. Clone this repository.

```bash
git clone https://github.com/goldenokeama/personal-dashboard.git
```

2. Open Google Chrome.

3. Navigate to:

```text
chrome://extensions
```

4. Enable **Developer mode**.

5. Click **Load unpacked**.

6. Select the project folder.

7. Open a new tab to view your personalized dashboard.

---

## 💻 How It Works

- When a new tab is opened, the extension:
  - Fetches a random nature image from the Unsplash API.
  - Displays the image as the page background.
  - Shows the photographer's name.
  - Retrieves live Dogecoin market data from CoinGecko.
  - Requests the user's location to fetch current weather.
  - Displays a real-time clock that updates every second.

---

## 🧠 Concepts Practiced

- Async/Await
- Fetch API
- Error handling with `try...catch`
- Working with REST APIs
- JavaScript Modules
- Browser Geolocation API
- DOM Manipulation
- Chrome Extension Development
- Manifest V3

---

## 🌱 Future Improvements

- Support multiple cryptocurrencies
- Display weather forecasts
- Allow users to choose background categories
- Add light and dark theme options
- Save user preferences using Chrome Storage API
- Display inspirational quotes or daily goals
- Add search shortcuts and productivity widgets

---

## 👨‍💻 Author

**Golden Okeama**  
JavaScript Developer passionate about modern web development and building interactive user experiences.
