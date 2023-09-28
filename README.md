# Weather App with User Registration and Login

This is a simple web application that combines user registration and login functionality with a weather information retrieval feature. Users can register, log in, and search for weather information for a specific city. The application is built using Node.js, Express, Firebase Firestore for user data storage, and the OpenWeather API to retrieve weather data.



## Prerequisites
Before you begin, ensure you have the following prerequisites installed:
- [Node.js](https://nodejs.org/): Make sure you have Node.js installed on your system.
- [Firebase](https://firebase.google.com/): You need a Firebase account and a project to obtain the Firebase Admin SDK key for Firestore.
- [OpenWeather API Key](https://openweathermap.org/api): You need an API key to fetch weather data.

## Installation
1. Clone this repository to your local machine
git clone https://github.com/your-username/weather-app.git

2. Install the required dependencies.
npm install


3. Place your Firebase Admin SDK key JSON file in the project root directory as `key.json`.

4. Replace `'cce84bc566550db3f65baa3be408d3a7'` in `public/js/script.js` with your OpenWeather API key.

## Usage
1. Start the application by running the following command:

bash
node server.js


2. Access the application in your web browser at `http://localhost:7000`.

3. Register a new user account by clicking on the "User Registration" link and filling in the required information.

4. Log in with your registered account using the "User Login" link.

5. After logging in, you can use the "Weather App" link to search for weather information for a specific city.

## Files
- `server.js`: The main Node.js server script that handles user registration, login, and serves the web pages.
- `public/js/script.js`: JavaScript file responsible for fetching weather data from the OpenWeather API and displaying it on the website.
- `public/views/register.html`: HTML form for user registration.
- `public/views/login.html`: HTML form for user login.
- `public/views/weather.html`: HTML form for weather data display.
- `key.json`: Firebase Admin SDK key JSON file (replace with your own).
- `.gitignore`: Git ignore file to exclude specific files and directories from version control.
