# 🌤️ Clim8: A Minimalistic Weather App

![Clim8 Logo](https://example.com/logo.png)

Welcome to **Clim8**, your go-to solution for checking the weather with a clean and minimalistic design. This application leverages the OpenWeather API to deliver accurate weather forecasts directly to your device. Whether you're planning a day out or just want to know if you need an umbrella, Clim8 has you covered.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [API Integration](#api-integration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Features

- **Simple Interface**: Enjoy a user-friendly experience with a clean layout.
- **Real-Time Weather Data**: Get live updates using the OpenWeather API.
- **Multi-City Support**: Check the weather for multiple locations.
- **Responsive Design**: Works well on both desktop and mobile devices.
- **Lightweight**: Fast loading times and minimal resource usage.

## Getting Started

To get started with Clim8, you need to clone the repository and set up your environment. Follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/zanella12/clim8.git
   ```

2. Navigate to the project directory:

   ```bash
   cd clim8
   ```

3. Install the necessary dependencies. Make sure you have Node.js installed:

   ```bash
   npm install
   ```

4. Set up your OpenWeather API key. You can sign up for a free account at [OpenWeather](https://openweathermap.org/api).

5. Create a `.env` file in the root directory and add your API key:

   ```plaintext
   OPENWEATHER_API_KEY=your_api_key_here
   ```

6. Start the application:

   ```bash
   npm start
   ```

## Usage

Once you have the application running, you can easily search for the weather in any city. Simply enter the city name in the search bar and hit enter. The app will display the current temperature, humidity, and a brief forecast.

### Example

- **City**: London
- **Temperature**: 15°C
- **Humidity**: 80%
- **Forecast**: Partly cloudy

## API Integration

Clim8 uses the OpenWeather API for fetching weather data. You can find more information about the API and its endpoints [here](https://openweathermap.org/api).

### API Key

To use the OpenWeather API, you must sign up for an API key. Insert your key in the `.env` file as described in the Getting Started section.

### Sample API Request

Here’s an example of how to make a request to the OpenWeather API:

```javascript
fetch(`https://api.openweathermap.org/data/2.5/weather?q=London&appid=${process.env.OPENWEATHER_API_KEY}`)
  .then(response => response.json())
  .then(data => console.log(data));
```

## Contributing

We welcome contributions to Clim8! If you want to help improve the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Commit your changes with a clear message.
5. Push your branch to your forked repository.
6. Create a pull request.

Please ensure your code follows the existing style and includes relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or feedback, feel free to reach out:

- **Email**: example@example.com
- **Twitter**: [@yourhandle](https://twitter.com/yourhandle)

## Releases

You can find the latest releases of Clim8 [here](https://github.com/zanella12/clim8/releases). Download the latest version and execute it to experience the latest features and improvements.

## Badges

![OpenWeather API](https://img.shields.io/badge/OpenWeather-API-blue.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## Acknowledgments

- **OpenWeather**: For providing the weather data.
- **Node.js**: For the backend environment.
- **React**: For building the user interface.

---

Thank you for checking out Clim8! We hope you enjoy using the app as much as we enjoyed building it. For updates and new features, keep an eye on the [Releases](https://github.com/zanella12/clim8/releases) section.