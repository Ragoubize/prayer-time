# 🕌 Morocco Prayer Times

A beautiful, responsive web application that displays daily prayer times for major Moroccan cities. This project was built to practice interacting with RESTful APIs using **JavaScript** and **Axios**.

![Project Screenshot](./screenshot.png)
<!-- 👆 If you have a screenshot, place it in your folder and name it 'screenshot.png', otherwise delete this line -->

## 🚀 About The Project

I created this project to deepen my understanding of asynchronous JavaScript and API integration. The goal was to build a functional dashboard that fetches real-time data from an external source and updates the DOM dynamically without reloading the page.

### Key Features:
- 🕒 **Real-time Data:** Fetches accurate prayer times (Fajr, Sunrise, Dhuhr, Asr, Maghrib, Isha).
- 📅 **Date Display:** Shows both Gregorian and Hijri dates with the day name.
- 🏙️ **City Selection:** Users can switch between various Moroccan cities (Casablanca, Rabat, Fes, Tangier, etc.).
- 🎨 **Modern UI:** Designed with Moroccan-inspired colors (Red & Green) featuring smooth animations and glassmorphism effects.
- 📱 **Responsive:** Looks great on desktop and mobile devices.

## 🛠️ Technologies Used

- **HTML5**: Semantic structure.
- **CSS3**: Custom styling, Flexbox, Grid, and Animations.
- **JavaScript (ES6+)**: DOM manipulation and Logic.
- **Axios**: A Promise-based HTTP client used to fetch data from the API.
- **Google Fonts**: 'Poppins' font for modern typography.

## 🔗 API Reference

This project uses the free and open-source **Aladhan API**:
- Endpoint used: `https://api.aladhan.com/v1/timingsByCity`
- Method: `GET`
- Parameters: `city`, `country`, `method` (set to 21 for Moroccan Awqaf Ministry standard).

## 📂 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ragoubize/prayer-time.git
