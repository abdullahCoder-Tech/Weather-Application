# Weather App ☀️🌧️🌡️

This Python program is a simple weather application that allows you to check the current weather for a city. It uses the OpenWeatherMap API to fetch weather information for a specified city and displays it in a user-friendly graphical interface built with the Tkinter library.

## Features 🌐
- Get the current weather for a city 🏙️.
- Display temperature in Celsius 🌡️.
- Show a weather icon to represent the current conditions 🌤️.
- Provide a description of the weather conditions 📋.
- Display the name of the city and its country 🌍.

## Installation 🛠️
This program requires the following Python libraries to be installed:
- tkinter
- requests
- PIL (Pillow)
- ttkbootstrap

You can install the required packages using pip:
```bash
pip install tkinter
pip install requests
pip install pillow
pip install ttkbootstrap
```

## Usage 💻
1. Run the program using a Python interpreter:

```bash
python weather_app.py
```

2. Enter the name of the city and click the "Search" button to fetch and display the weather information.

## API Key
This application uses the OpenWeatherMap API to fetch weather data. You need to obtain an API key from OpenWeatherMap and replace the `API_key` variable in the code with your own API key.

```python
API_key = "YOUR_API_KEY"
```

## Important Note
Please note that this program has a knowledge cutoff date of January 2022, and the functionality may be affected if the API or libraries have undergone significant changes after that date.

## License 📄
This project is open-source and available under the [MIT License](LICENSE).

## Credits 💡
- Python: [python.org](https://www.python.org/)
- Tkinter: [Tkinter Documentation](https://docs.python.org/3/library/tkinter.html)
- OpenWeatherMap API: [OpenWeatherMap](https://openweathermap.org/)
- ttkbootstrap: [ttkbootstrap Documentation](https://ttkbootstrap.com/)

Enjoy checking the weather with this simple and stylish weather app! 🌞🌧️🌈