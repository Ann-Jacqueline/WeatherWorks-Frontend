# Weatherworks Vue JS Weather App

This is the frontend component of the Weatherworks Vue JS Weather App, 
which is architected with a frontend component and a backend component linked to a PostgreSQL database.
[WeatherWorks-Backend Repository](https://github.com/Ann-Jacqueline/backend-webtech).

## About the Project

The app was developed by myself, Ann-Jacqueline Viola Kaldjob, 
as part of my Web Technologies module of the third semester 
at the University of Applied Sciences for Technology and Economics Berlin (HTW Berlin).

## Functionality

The central functionality of this Vue JS component includes:
- Data retrieval
- Data flow management
- Data exchange with the backend and the PostgreSQL database using axios requests

## Data Management

Responsible for this frontend-side management is the management store, which:
- Centrally supplies all Vue components with data
- Extracts data
- Exchanges data with the backend via POST, GET, or DELETE requests

This creates an interlinked system where data management functions dually, 
with the frontend-side managed by the management store and the backend-side handled 
by the PostgreSQL database.

