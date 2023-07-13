# Weather Fetcher

This Python script fetches weather details from the OpenWeatherMap API based on user input. It provides the option to retrieve weather information either by city name or pincode.

## Features

- Fetch weather details by city name or pincode
- Retrieve weather data such as temperature, humidity, wind speed, and weather description
- Easy-to-use command-line interface

## Installation

1. Clone the repository:

```
git clone https://github.com/bitphonix/weather-fetcher.git
```

2. Install the required dependencies:

```
pip install requests
```

## Usage

1. Run the script:

```
python weather_fetcher.py
```

2. Enter the corresponding option to fetch weather details:
   - Enter `1` to fetch weather by city.
   - Enter `2` to fetch weather by pincode.

3. Provide the required input (city name or pincode) when prompted:
   - Enter your city name: `<city_name>`
   - or
   - Enter your pincode: `<pincode>`

4. The script will retrieve and display the weather information.

## API Key

This script uses the OpenWeatherMap API to fetch weather data. To make API requests, you need to obtain an API key from OpenWeatherMap and replace the `api_key` variable in the script with your own API key.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to contribute and make improvements! If you encounter any issues or have suggestions, please open an issue in the issue tracker.
