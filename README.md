# 🌦️ WeatherApp

![WeatherApp](https://img.shields.io/badge/WeatherApp-Open%20Source-brightgreen)

Welcome to **WeatherApp**, your go-to application for checking the weather in any city. Built using modern technologies, this app utilizes the powerful open-meteo.com API to deliver accurate and timely weather information.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- 🌍 **City-Based Weather Information**: Check the weather for any city around the globe.
- 📅 **Forecasting**: Get forecasts for the upcoming days.
- 🌡️ **Temperature Display**: View current temperatures in Celsius and Fahrenheit.
- 📊 **Visual Data Representation**: Graphs and charts for better understanding of weather trends.
- 📦 **Docker Support**: Easy deployment with Docker.
- ⚡ **FastAPI Backend**: High performance and easy to use.
- 🌐 **Responsive Design**: Works well on both desktop and mobile devices.

## Technologies Used

This project leverages a variety of technologies to deliver a seamless experience:

- **Backend**: 
  - FastAPI
  - Redis
  
- **Frontend**: 
  - HTML
  - CSS
  
- **Deployment**: 
  - Docker
  - Nginx
  
- **Monitoring**: 
  - Prometheus
  - Loki
  - Promtail
  
- **Programming Language**: 
  - Python (Python 3)

## Getting Started

To get started with WeatherApp, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SOUMIK002/WeatherApp.git
   cd WeatherApp
   ```

2. **Install Dependencies**:
   Make sure you have Python 3 installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   Start the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```

4. **Access the App**:
   Open your web browser and go to `http://localhost:8000`.

## Usage

Once you have the app running, you can start checking the weather:

1. **Enter City Name**: Type the name of the city in the input box.
2. **View Weather**: Click the "Check Weather" button to view the current weather and forecast.

## Deployment

For deploying WeatherApp, you can use Docker. Here’s how:

1. **Build the Docker Image**:
   ```bash
   docker build -t weatherapp .
   ```

2. **Run the Docker Container**:
   ```bash
   docker run -d -p 80:80 weatherapp
   ```

3. **Access the App**: Open your browser and navigate to `http://localhost`.

## Releases

You can download the latest release of WeatherApp from the [Releases section](https://github.com/SOUMIK002/WeatherApp/releases). Make sure to download the appropriate file for your system and execute it to get started.

## Contributing

We welcome contributions to improve WeatherApp. Here’s how you can help:

1. **Fork the Repository**: Click the "Fork" button on the top right.
2. **Create a Branch**: 
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make Changes**: Implement your changes and commit them.
4. **Push to Your Fork**:
   ```bash
   git push origin feature/YourFeature
   ```
5. **Create a Pull Request**: Submit a pull request for review.

## License

WeatherApp is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the license terms.

## Contact

For any inquiries, feel free to reach out:

- **Author**: Soumik
- **GitHub**: [SOUMIK002](https://github.com/SOUMIK002)

Thank you for checking out WeatherApp! We hope you find it useful for all your weather-related needs. Don't forget to visit the [Releases section](https://github.com/SOUMIK002/WeatherApp/releases) for the latest updates and features.