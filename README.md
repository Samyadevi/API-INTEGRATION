# API-INTEGRATION

"COMPANY": CODTECH IT SOLUTIONS

"NAME": BADA SAMYADEVI

"INTERN ID": CT04DG512

"DOMAIN": FULL STACK WEB DEVELOPMENT

"DURATION": 4 WEEKS

"MENTOR": NEELA SANTOSH

DESCRIPTION :
🌦️ Weatherly: Your Personal Weather Checker
Overview
Weatherly is a responsive and user-friendly web application providing instant weather updates and forecasts for any global location. Built with HTML, CSS, and JavaScript, it leverages the powerful WeatherAPI to deliver real-time current conditions, a 3-hour hourly forecast, and an extended 7-day daily forecast. The application emphasizes a clean, intuitive design with a beautiful, dynamic background, making checking the weather a pleasant and informative experience for users across various devices.

Key Features
Responsive Layout: The webpage automatically adjusts its layout for optimal viewing on any screen size, from desktops to mobile devices. Input fields and buttons become more compact on smaller screens, ensuring usability.

Dynamic Content Loading: Weather data is fetched and displayed without requiring a page reload. This functionality, powered by the JavaScript Fetch API, provides a smooth, interactive experience.

Error Handling: Robust error handling is included. If a user inputs an invalid city or if there's an issue with the API call, a clear error message provides immediate feedback.

Current & Hourly Forecasts: Get immediate access to the current temperature for any searched location, along with a concise 3-hour outlook showing temperature, time, and weather conditions with illustrative icons.

Comprehensive 7-Day Forecast: Look further ahead with a detailed 7-day forecast. Each card displays the day, average temperature, and descriptive weather condition with an accompanying icon, significantly aiding long-term planning.

Dynamic Background & Modern Aesthetics: Features a visually appealing background image with a subtle overlay, enhancing aesthetics while ensuring content readability. It incorporates modern web design principles like backdrop-filter: blur() for a frosted glass effect, soft shadows, and rounded borders.

Live Clock Display: A subtle live clock is integrated into the header, showing the current local time alongside weather information, adding an extra layer of utility.

Technical Stack
HTML5: Provides the fundamental structure and content of the web page, using semantic elements for accessibility.

CSS3: Styles the application, defining its visual presentation and layout. Key features include:

Flexbox: For efficient and flexible layout management of containers and forecast cards.

background-size: cover and background-attachment: fixed: For an engaging, non-scrolling background image.

backdrop-filter: blur(): Creates the "frosted glass" effect on content panels.

@media queries: Ensures adaptability across various device sizes.

JavaScript (ES6+): Powers dynamic functionality, including:

Fetch API: For asynchronous data retrieval from WeatherAPI.com.

DOM Manipulation: Displays current weather, hourly, and 7-day forecasts.

Client-side input validation and real-time live clock updates.

Error handling for API requests.

How It Works
Weatherly uses WeatherAPI (weatherapi.com) to retrieve data. When a user enters a location and clicks "Get Temperature & Forecast":

User Interface (UI) Interaction: Users enter a city name into the search bar and click the "Get Temperature & Forecast" button.

API Integration (WeatherAPI): The getWeather() JavaScript function is called. It constructs an API request URL to http://api.weatherapi.com/v1/forecast.json including the city, API Key, and days=7 for forecast data.

Data Processing & DOM Manipulation: Upon a successful JSON response, current conditions, 3-hour hourly forecast, and 7-day daily forecast data are extracted. This information is then dynamically injected into the #result and #sevenDayForecast HTML elements, updating the UI in real-time.

Error Handling: If the fetch request encounters an issue (e.g., "Location not found"), a user-friendly error message is displayed.

A live clock updates every second via setInterval, and the footer year is set on page load.

Setup and Usage
To run this project locally:

Get an API Key from WeatherAPI.com: Sign up for a free developer account on WeatherAPI.com to obtain your unique API key.

Create the Webpage: Save the provided HTML code as index.html. Open it in a text editor.

Insert your API Key: Locate const API_KEY = "416570dda2d649bebb6134924250606"; within the <script> tags and replace the placeholder with your actual API key.

Open in browser: Simply double-click index.html. Enter a location (e.g., "Paris") and click "Get Temperature & Forecast".

OUTPUT :

![Image](https://github.com/user-attachments/assets/d2c3f21a-fcdd-4f6f-b627-e165550c58d3)

![Image](https://github.com/user-attachments/assets/de5945b8-c0aa-4053-af53-7965ef63b933)
