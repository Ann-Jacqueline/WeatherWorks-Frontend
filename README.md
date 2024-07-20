# Weatherworks Vue JS Weather App

![WeatherWorks](https://github.com/Ann-Jacqueline/backend-webtech/blob/main/WeatherWorks.gif)

This is the frontend component of the Weatherworks Vue JS Weather App, designed to provide a seamless user interface for weather data interaction utilizing a Management store.ts to productivly comunicated to the WeatherWorks backend component that is linked  to a PostgreSQL database.

[WeatherWorks-Backend Repository](https://github.com/Ann-Jacqueline/backend-webtech)

## About the Project

This application was developed by Ann-Jacqueline Viola Kaldjob as part of the Web Technologies module during the third semester at the University of Applied Sciences for Technology and Economics Berlin (HTW Berlin).

## Functionality

The central functionality of this Vue JS component includes:

- **Visual/UI Interface:** The main display of the Weather App provides an intuitive and user-friendly interface.
- **City Overview:** Retrieve and display an overview of a city using an external API key.
- **User Input Management:**
  - Save user input through a city search function.
  - Pin a default city and change it as needed.
  - Manage locations by adding or deleting cities.
    
- **Settings:** Allow users to set unit preferences (°C or °F).
- **Error Handling:** Handle incorrect city searches gracefully.
- **Multiuser Functionality:** Enable login and logout features for multiple users.
  
- **Data Interaction:**
  - Data retrieval.
  - Data flow management.
  - Data exchange with the backend and PostgreSQL database using axios requests.

## Data Management

The management store is responsible for frontend-side data management. It:

- Centrally supplies all Vue components with data.
- Extracts and processes data.
- Exchanges data with the backend via POST, GET, or DELETE requests.

This creates an interlinked system where data management is handled both on the frontend and backend sides, ensuring seamless data synchronization between the Vue JS application and the PostgreSQL database.

---


