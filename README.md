[![Apriome](/.public/showcase.png)](https://dev-aligator.github.io/apriome/)

<p align="center">
  <a aria-label="try apriome in the browser" href="https://dev-aligator.github.io/apriome/"><b>Try in the Browser</b></a>
</p>

# Anime Recommendations System

This repository encompasses the frontend and backend modules of the Anime Recommendations System, aimed at providing personalized anime suggestions based on user preferences.

## Modules

### Anime Recommendation Backend (`animerecs-backend`)

The backend module is built with Django, a high-level Python web framework. It provides RESTful API endpoints for managing user authentication, storing anime data, and generating recommendations dynamically. Key features include:

- **Authentication**: Registering new users, user login/logout functionality.
- **Anime Data Management**: CRUD operations for anime entries.
- **Recommendations**: Endpoint for fetching personalized anime recommendations.

### Anime Recommendation Frontend (`animerecs-frontend`)

The frontend module utilizes React, TypeScript, Tailwind CSS, and SASS to create an interactive user interface for accessing anime recommendations. It communicates with the backend API to fetch and display anime data. Key features include:

- **User Interface**: Intuitive and user-friendly design for browsing anime recommendations.
- **Authentication**: Secure authentication system for managing user sessions.
- **Dynamic Rendering**: Dynamically fetches and updates anime data from the backend.
- **Responsive Design**: Ensures optimal viewing experience across various devices and screen sizes.

## Stack Summary

### Backend Stack
- **Framework**: Django
- **Database**: SQLite (can be replaced with other databases supported by Django)
- **Authentication**: Django Authentication System
- **API**: Django REST Framework

### Frontend Stack
- **Framework**: React
- **Styling**: Tailwind CSS, SASS
- **State Management**: React Hooks
- **API Communication**: Axios

## Setup and Usage

For detailed setup instructions and usage guidelines, please refer to the respective README files in the `animerecs-backend` and `animerecs-frontend` submodules.

---
<p align="center">Dev-Aligator</p>
<p align="center">
<a href="https://github.com/Dev-Aligator/">
<img src="https://user-images.githubusercontent.com/58631762/120077716-60cded80-c0c9-11eb-983d-80dfa5862d8a.png" width="19">
</a>