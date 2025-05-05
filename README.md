# Weather App - Java Servlet JSP

## Overview
This is a dynamic web application built using Java Servlets and JSP (JavaServer Pages). The application fetches real-time weather data from the OpenWeather API and displays it to the user. Users can search for weather details of any city and view information such as temperature, humidity, wind speed, visibility, and more.

## Features
- Fetches real-time weather data using the OpenWeather API.
- Displays weather details such as temperature, humidity, wind speed, visibility, and cloud cover.
- User-friendly interface with a search form to input city names.
- Dynamic rendering of weather details using JSP.

## Project Structure
```
weather-app-javaServletJSP/
├── build/
│   └── classes/
│       └── MyPackage/
│           └── MyServlet.class
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── MyPackage/
│   │   │       └── MyServlet.java
│   │   ├── webapp/
│   │   │   ├── index.html
│   │   │   ├── index.jsp
│   │   │   ├── jsp-style.css
│   │   │   ├── script.js
│   │   │   ├── style.css
│   │   │   ├── images/
│   │   │   │   └── img1.png
│   │   │   ├── META-INF/
│   │   │   │   └── MANIFEST.MF
│   │   │   └── WEB-INF/
│   │   │       ├── web.xml
│   │   │       └── lib/
│   │   │           └── gson-2.8.5.jar
```

## Key Files

### 1. `MyServlet.java`
- Handles HTTP GET and POST requests.
- Integrates with the OpenWeather API to fetch weather data.
- Processes the API response and forwards the data to `index.jsp` for rendering.

### 2. `index.html`
- The landing page of the application.
- Contains a form for users to input the city name and submit the request.

### 3. `index.jsp`
- Dynamically displays the weather details fetched from the OpenWeather API.
- Uses JSP expressions to render data such as temperature, humidity, and weather conditions.

### 4. `web.xml`
- Configures the servlet mapping for `MyServlet`.
- Defines the welcome files for the application.

## Prerequisites
- Java Development Kit (JDK) 11 or higher.
- Apache Tomcat server.
- Internet connection for API requests.

## Setup Instructions
1. Clone the repository or download the project files.
2. Import the project into your favorite IDE (e.g., Eclipse, IntelliJ IDEA).
3. Add the `gson-2.8.5.jar` library to your project's build path.
4. Deploy the project to an Apache Tomcat server.
5. Access the application in your browser at `http://localhost:<port>/weather-app-javaServletJSP`.

## Usage
1. Open the application in your browser.
2. Enter the name of a city in the search form and click "Get Weather".
3. View the weather details displayed on the page.

## Technologies Used
- Java Servlets
- JSP (JavaServer Pages)
- HTML, CSS, JavaScript
- OpenWeather API
- Gson library for JSON parsing

## Author
Developed by VinyasCS @ 2025.

## License
This project is licensed under the MIT License.