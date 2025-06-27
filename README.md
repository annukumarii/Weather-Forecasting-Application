# Weather-Forecasting-Application

1 . A simple and elegant weather application built using **React**, **Styled Components**, and the **OpenWeatherMap API**. Users can search for any city to get real-time weather updates including temperature, weather condition, and icons representing the weather visually.

---

## Features

- Search weather by **city name**
- Displays weather conditions using beautiful **icons**
- Fetches live data from **OpenWeatherMap API**
- Built with **React functional components** and **hooks**
- Styled using **Styled Components** and responsive CSS

---

##  Tech Stack

- **React JS**
- **Styled Components**
- **Axios** for HTTP requests
- **OpenWeatherMap API**

---

2. Install Dependencies
npm Install

3. Configure the API Key

Open the App.js file and replace the placeholder API key with your own key from OpenWeatherMap:
const response = await Axios.get(
  `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=YOUR_API_KEY`,
);
4. npm start

The application will run at http://localhost:3000.

---

Thank you for using the Weather Forecasting Application.  
Feel free to explore, use, or improve it as needed.
