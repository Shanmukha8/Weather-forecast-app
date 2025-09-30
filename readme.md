# Weather Forecast App 🌤️

A responsive web application that provides real-time weather information for cities around the world using the OpenWeatherMap API.

## Features

- **Real-time Weather Data**: Fetches live weather information for any city worldwide
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Interactive UI**: Clean and modern interface with smooth animations
- **Comprehensive Weather Info**: Displays temperature, humidity, wind speed, pressure, and weather conditions
- **Error Handling**: Graceful error messages for invalid city names or API issues
- **Dynamic Icons**: Weather condition icons that update based on current weather

## Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling with flexbox, grid, and animations
- **JavaScript (ES6+)**: Async/await for API calls and DOM manipulation
- **OpenWeatherMap API**: Weather data provider

## Project Structure

```
Weather-forecast-app/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript logic
└── README.md          # Project documentation
```

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shanmukha8/Weather-forecast-app.git
   cd Weather-forecast-app
   ```

2. **Get API Key**
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Generate your API key from the dashboard

3. **Configure API Key**
   - Open `script.js`
   - Replace `'YOUR_API_KEY_HERE'` with your actual API key:
     ```javascript
     const API_KEY = 'your_actual_api_key';
     ```

4. **Run the Application**
   - Open `index.html` in your web browser
   - Or use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```

## Usage

1. Enter a city name in the search box
2. Click the "Search" button or press Enter
3. View real-time weather information including:
   - Current temperature
   - Weather description
   - Feels like temperature
   - Humidity percentage
   - Wind speed
   - Atmospheric pressure

## Key Skills Demonstrated

- HTML5 semantic structure
- CSS3 modern layouts (Flexbox & Grid)
- Responsive web design
- JavaScript ES6+ features
- Asynchronous programming with async/await
- API integration and error handling
- DOM manipulation
- Event handling
- Mobile-first design approach

## Screenshots

*Add screenshots of your application here*

## API Reference

This project uses the [OpenWeatherMap Current Weather Data API](https://openweathermap.org/current)

**Endpoint**: `https://api.openweathermap.org/data/2.5/weather`

**Parameters**:
- `q`: City name
- `appid`: Your API key
- `units`: metric (for Celsius)

## Future Enhancements

- [ ] 5-day weather forecast
- [ ] Geolocation support
- [ ] Search history
- [ ] Multiple unit systems (Celsius/Fahrenheit)
- [ ] Weather alerts and notifications
- [ ] Dark mode toggle

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**Shanmukha**
- GitHub: [@Shanmukha8](https://github.com/Shanmukha8)

## Acknowledgments

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
- Icons from OpenWeatherMap API

---

**Note**: This project was created as part of a portfolio demonstration of web development skills including API integration, responsive design, and modern JavaScript practices.