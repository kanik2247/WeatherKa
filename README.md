# WeatherKa
A simple weather application that allows users to search for the current weather conditions in any location. This app uses the OpenWeatherMap API to fetch weather data.

## Features

- Search for weather by city name.
- Display temperature, weather condition, humidity, and wind speed.
- Responsive design for desktop, tablet, and mobile devices.

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Setup Instructions

1. **Clone the repository**

   ```sh
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   
2. **Open 'index.html'**

Open index.html in your preferred web browser.

3. **API Key**
Replace the placeholder API key in script.js with your own OpenWeatherMap API key. Sign up at OpenWeatherMap to get a free API key.
const APIKey = 'your_api_key_here';

4. **Run the Application**
Simply open the index.html file in a web browser to run the application.


                                           OR
   
You can access the Weather App [here](https://weatherka.netlify.app/).
   

## File Structure

**index.html**: The main HTML file containing the structure of the web page.
**styles.css**: The CSS file for styling the application.
**script.js**: The JavaScript file that contains the logic for fetching and displaying weather data.
**images/**: Folder containing weather condition images.

## Approach

**Design and Layout** : The design is clean and simple, making use of the Poppins font for a modern look. The layout consists of a search box at the top, followed by the weather display area, and weather details (humidity and wind speed) at the bottom.
**Responsive Design**:Media queries are used to ensure the app is responsive and works well on devices of various sizes:
For tablets (max-width: 768px), font sizes and paddings are adjusted.
For mobile phones (max-width: 480px), the layout is changed to a column direction to ensure elements do not overlap.

## Fetching Weather Data
The app fetches weather data from the OpenWeatherMap API using the Fetch API in JavaScript. Depending on the weather conditions, appropriate images are displayed.

## Challenges

**Responsive Design** :  Ensuring that the layout looks good on various devices was challenging. The initial approach had issues with overlapping elements on smaller screens. This was resolved by adjusting flex properties and layout direction for smaller screens.

**API Integration** :Fetching and handling API data required careful handling of possible error cases, such as invalid city names or network issues.
