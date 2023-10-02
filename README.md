# weather-app
website for weather application

Please note that your weather app is still unable to show the weather forecast for any location because you’ve not provided your OpenWeatherMap API key in the API_KEY variable. To get a free API key, sign up for an account at https://home.openweathermap.org/api_keys. Your API key may take minutes or hours to activate. You’ll get an error like “Invalid API Key” or something similar during this time.

In the code, there are two API calls. The first one fetches the geographic coordinates of the user-entered city. These coordinates are then used in the second API call to retrieve the weather forecast, which is displayed on the page. The code also includes a feature that asks for user location permission and, once granted, makes the second API call to fetch the weather forecast based on the user’s current location.

