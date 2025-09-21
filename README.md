# Weather-app
A simple command-line Python app that fetches and displays real-time weather for a user-specified location. It shows city, state, and country along with temperature, humidity, and conditions using the OpenWeatherMap API. Ideal for beginners learning APIs and Python basics.
🎯 Objective

Create a Python application to provide current weather information for a user-specified city.

Basic Version: Fetches and displays temperature, humidity, and weather conditions in the console.

Advanced Version: Provides a GUI, dynamic weather details, and weather icons using Tkinter.

🛠️ Steps Performed
🔹 Basic Version

Collected city input from the user.

Fetched weather data using OpenWeatherMap API.

Parsed JSON response to extract temperature, humidity, and weather condition.

Displayed the result in the console.

🔹 Advanced Version

Built a Tkinter GUI for user-friendly interaction.

Allowed dynamic city input and fetch on button click.

Displayed temperature, feels like, humidity, wind speed, and weather condition.

Fetched and displayed weather icons dynamically.

Implemented error handling for invalid city names or network issues.

⚙️ Tools & Technologies Used

Python

Libraries:

requests – API calls

json – Parsing API responses

tkinter – GUI interface

Pillow (PIL) – Displaying weather icons

messagebox – Displaying warnings and errors

✅ Outcome

Basic Version: Provides current weather info in the console.

Advanced Version: User-friendly GUI displaying weather info and icons dynamically.

Demonstrates API integration, JSON parsing, GUI design, and real-time data visualization.
🚀 Future Enhancements

Add 5-day or weekly forecast.

Automatically detect user location for instant weather info.

Show additional data such as sunrise/sunset, air quality, and UV index.

Enhance GUI with themes, responsive layout, and animations.

Include unit conversion (Celsius/Fahrenheit).
