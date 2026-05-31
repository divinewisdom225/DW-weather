# DW Weather & Cam

A beautiful, real-time weather application with webcam background, hourly forecasts, and 14-day predictions.

## Features

✨ **Real-time Weather Data** - Current conditions with temperature and forecasts
📱 **Responsive Design** - Works on all devices (mobile, tablet, desktop)
🎥 **Live Webcam** - Background video from your device camera
⏰ **Auto-Refresh** - Updates every 10 minutes automatically
📦 **Persistent Storage** - Remembers your last searched city
🎨 **Beautiful UI** - Google-style glassmorphism design
📊 **Multiple Forecasts** - 8-hour hourly + 14-day extended forecast
🎭 **Weather Animations** - Dynamic icons based on weather conditions

## How to Use

1. Visit: [https://divinewisdom225.github.io/DW-weather/](https://divinewisdom225.github.io/DW-weather/)
2. Enter a city name (e.g., "London", "Tokyo", "Lagos")
3. Press Enter to get weather data
4. View hourly and 14-day forecasts
5. Switch between Temperature, Precipitation, and Wind data

## Features in Detail

### Auto-Refresh
- Automatically updates weather every 10 minutes
- Shows cached data from localStorage instantly
- Never loses your data

### Weather Animations
- ☀️ **Sunny** - Floating animation
- 🌧️ **Rainy** - Falling animation
- ⛈️ **Thunderstorm** - Shaking animation
- ❄️ **Snow** - Drifting animation

### Forecasts
- **8-Hour Hourly** - Temperature, precipitation chance, wind speed
- **14-Day Extended** - High/low temperatures for 2 weeks
- **Interactive Tabs** - Switch between different forecast types

## Technology Stack

- **HTML5** - Structure
- **CSS3** - Styling with animations and glassmorphism
- **JavaScript** - Vanilla JS (no frameworks)
- **OpenWeatherMap API** - Weather data
- **LocalStorage** - Persistent data

## API

Uses the free OpenWeatherMap API:
- Current weather data
- 5-day forecast (3-hour intervals)

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Permissions

The app may request:
- **Camera access** - For live webcam background (optional, can be denied)
- **Location** - Not used, but you can enter city manually

## Tips

💡 **Search tips:**
- Use city names (e.g., "Paris", "New York")
- Use with country codes (e.g., "London,UK", "Paris,FR")
- Use zip codes (e.g., "90210")

⚡ **Performance:**
- Data is cached locally for fast loading
- Only fetches new data when refreshing
- Smooth animations optimized for all devices

---

## 🚀 Powered by Divine Wisdom

[GitHub Profile](https://github.com/divinewisdom225)

Made with ❤️ for weather enthusiasts
