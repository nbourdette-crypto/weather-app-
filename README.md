(Features)
Real-time Data: Fetches live weather updates using the OpenWeatherMap API.

Dynamic Backgrounds: The app background changes visually based on conditions like "Clouds," "Rain," "Clear," or "Mist."

Smart Search: Users can search by city name using the search button or by pressing the Enter key.

Metric to Imperial Conversion: Automatically calculates and displays temperature in Fahrenheit.

Error Handling: Displays a clear "Invalid city name" message if the search query does not match a known location.

Detailed Metrics: Shows essential weather data including:

Current Temperature

Humidity Percentage

Wind Speed km/h

(how it works)
User Input: The user enters a city name into the input field.

API Call: When the search is triggered, the app sends an asynchronous GET request to the OpenWeatherMap API using a unique API key.

Data Processing: * The app checks the response status. If a 404 error occurs, it reveals an error message.

If successful, it parses the JSON data to extract the city name, temperature, humidity, and wind speed.

Visual Update

(TECH used in the project)
HTML5: Structure of the web application.

CSS3: Styling, layout, and smooth background transitions.

JavaScript (ES6): Fetch API for data retrieval and DOM manipulation for dynamic updates.

OpenWeatherMap API: The data source for global weather information.


