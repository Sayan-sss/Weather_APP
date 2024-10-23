
# Weather App

Welcome to the **Weather App**! This web application provides real-time weather data for any location in the world. The app is powered by the OpenWeather API and built using modern web technologies such as **React**, **CSS**, and **JavaScript**. Deployed on **Vercel**, this project aims to deliver a simple yet effective way to check the current weather conditions by simply entering the name of a city.

### [Deployed Link](https://weather-app-ivory-xi.vercel.app/)

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Integration](#api-integration)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **Search for Weather**: Enter the name of any city to get real-time weather data.
- **Real-Time Updates**: Displays current temperature, weather conditions, humidity, wind speed, and more.
- **Responsive Design**: Works seamlessly on both mobile and desktop devices.
- **Error Handling**: Provides user-friendly error messages for invalid inputs or city names.
- **Dynamic Background**: Changes background image based on the weather condition of the searched location.

---

## Technologies Used

- **Frontend**:
  - [React](https://reactjs.org/) - JavaScript library for building user interfaces.
  - [CSS3](https://www.w3.org/Style/CSS/) - For styling the application.
  - [JavaScript](https://www.javascript.com/) - Logic for fetching and rendering weather data.

- **Backend**:
  - [OpenWeather API](https://openweathermap.org/api) - Fetching weather data.

- **Deployment**:
  - [Vercel](https://vercel.com/) - For seamless deployment and hosting.

---

## Installation

### Prerequisites:
- **Node.js** (>=14.x)
- **npm** or **yarn**

### Steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Sayan-sss/Weather_APP.git
   ```

2. Navigate into the project directory:
   ```bash
   cd Weather_APP
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add your OpenWeather API key:
   ```bash
   REACT_APP_OPENWEATHER_API_KEY=your_api_key_here
   ```

   You can obtain an API key from [OpenWeather](https://openweathermap.org/api).

5. Start the development server:
   ```bash
   npm start
   ```

6. Open your browser and navigate to `http://localhost:3000` to view the app.

---

## Usage

1. **Search**: Enter the name of a city in the input field and click the search button.
2. **View Weather Data**: The app will display the weather details such as:
   - Temperature (in Celsius)
   - Weather conditions (Clear, Cloudy, Rainy, etc.)
   - Humidity
   - Wind speed
   - Weather icon representing the condition.
3. **Dynamic Updates**: Based on the search result, the background image changes to reflect the weather condition (e.g., clear skies, rain, clouds).

---

## API Integration

This app uses the [OpenWeather API](https://openweathermap.org/api) to fetch real-time weather data. The integration occurs in the following steps:

1. The user enters a city name.
2. A GET request is sent to OpenWeather API using the entered city name.
3. The app receives the weather data and processes it to display:
   - Temperature
   - Weather description
   - Humidity
   - Wind speed
   - An icon representing the weather condition

Make sure you have your API key set up in the `.env` file as explained in the [Installation](#installation) section.

---

## Folder Structure

```
Weather_APP/
│
├── public/
│   └── index.html          # The main HTML file
├── src/
│   ├── components/         # React components
│   ├── App.js              # Main application component
│   ├── index.js            # ReactDOM rendering
│   ├── Weather.js          # Component for fetching and displaying weather data
│   └── App.css             # Styling for the application
│
├── .env                    # Environment variables (API Key)
├── package.json            # Project metadata and dependencies
└── README.md               # Project documentation
```

---

## Contributing

Contributions are welcome! If you have suggestions for new features or improvements, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy coding! 😊 If you find this project helpful, feel free to give it a star on GitHub!

--- 

### Contact

For any queries or suggestions, feel free to reach out:

- **GitHub**: [Sayan-sss](https://github.com/Sayan-sss)
- **Deployed Link**: [Weather App](https://weather-app-ivory-xi.vercel.app/)
