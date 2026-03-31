Weather Application using Java Servlet and JSP
1. Overview

This project is a web-based Weather Application developed using Java Servlets and JavaServer Pages (JSP). The application allows users to enter a city name and retrieve real-time weather information. It uses the OpenWeatherMap API to fetch weather data and displays details such as temperature, humidity, wind speed, visibility, and cloud coverage.

The main goal of this project is to demonstrate how backend Java technologies can interact with external APIs and display dynamic data on a web interface.

2. Features
Search weather by city name
Displays temperature, humidity, and wind speed
Shows visibility and cloud coverage
Fetches real-time data using OpenWeatherMap API
Simple user interface

3. Technologies Used
Java
Java Servlets
JavaServer Pages (JSP)
HTML
CSS
JavaScript
Apache Tomcat Server
Gson Library (JSON parsing)
OpenWeatherMap API

4. Project Structure
   Weather-App
│
├── src/main/java/MyPackage
│   └── MyServlet.java
│
├── src/main/webapp
│   ├── index.html
│   ├── index.jsp
│   ├── style.css
│   └── script.js
│
└── WEB-INF
    └── web.xml

5.  How It Works
The user enters a city name in the web interface.
The request is sent to a Java Servlet.
The servlet calls the OpenWeatherMap API.
The API returns weather data in JSON format.
The Gson library parses the JSON response.
The processed data is sent to a JSP page.
The JSP page displays the weather information to the user.

   
6. Installation and Setup
  1. Prerequisites

Make sure the following tools are installed:

Java JDK
Apache Tomcat Server
Eclipse IDE or IntelliJ IDEA
Internet connection for API access
  2. Clone the Repository
git clone https://github.com/your-username/weather-app.git
  3. Import the Project

Import the project into Eclipse or IntelliJ IDEA as a Dynamic Web Project.

  4. Add Dependencies

Download the Gson library and place it inside the WEB-INF/lib folder.

  5. Configure API Key

Create an account at OpenWeatherMap and generate an API key. Replace the API key inside MyServlet.java.

  6. Run the Project

Deploy the project on Apache Tomcat Server and open:

http://localhost:8080/WeatherApp

7.API Used

OpenWeatherMap API is used to retrieve real-time weather information for different cities.

8. Future Improvements
Add weather icons and better UI design
Support for multiple languages
Display 7-day weather forecast
Add location-based weather detection
