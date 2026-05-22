# CLI Weather Checker

A terminal-based Python utility that fetches and displays live global weather information using the OpenWeatherMap API.

## Features

- **Live Data Fetching**: Sources real-time temperatures and local parameters globally.
- **Metric System Parsing**: Formats system values automatically to standard Metric degrees Celsius (°C).
- **Graceful Error Feedback**: Tracks and prints explicit error messages from the server if a city isn't found.

## Prerequisites

- Python 3.x
- Third-party HTTP client library:
  ```bash
  pip install requests
  ```

## API Configuration

This application requires an active API key from OpenWeatherMap:
1. Register for a free account at [OpenWeatherMap](https://openweathermap.org/).
2. Generate your unique API token.
3. Open `main.py` and assign your credential string directly to the global config variable:
   ```python
   API_KEY = 'YOUR_API_KEY_HERE'
   ```

## How to Run

1. Save the code to a file named `main.py`.
2. Open your system terminal.
3. Run the application:
   ```bash
   python main.py
   ```

## Usage Guide

1. Input a target city name at the terminal command prompt (e.g., `London` or `Tokyo`).
2. Review the structured summary output including raw temperature, human sensory approximation, and ambient humidity.
3. Type `quit` at the entry prompt to close out the script loop.
