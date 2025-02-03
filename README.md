# PRODIGY_WD_05

# Weather App 🌤️

This is a simple weather application that fetches real-time weather data using a weather API. Users can search for weather conditions based on their current location or by inputting a custom location.

---

## Features
- Displays current weather conditions, temperature, and description.
- Fetches data from a weather API.
- Responsive and visually appealing interface with a background image.
- User-friendly input and dynamic data display.

---

## How to Use the API

1. **Get an API Key**:  
   - Visit [OpenWeatherMap](https://openweathermap.org/) and create a free account.  
   - Navigate to the "API Keys" section in your account and generate a new API key.

2. **Add Your API Key**:  
   - Open the `script.js` file in this project.  
   - Replace `YOUR_API_KEY_HERE` with the API key you generated:  
     ```javascript
     const apiKey = 'YOUR_API_KEY_HERE';
     ```

3. **Understand the API Call**:  
   The application sends a request to the OpenWeatherMap API using the following structure:  
   ```url
   https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}
