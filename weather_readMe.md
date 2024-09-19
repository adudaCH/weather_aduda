
# Weather API Application

## Overview
This is a simple Weather API Application that allows users to enter a city name and receive the current weather information for that location. The application displays the city name, temperature, weather description, and an associated weather icon.

## Technologies Used
- **HTML5**: For the structure and layout of the application.
- **CSS3**: For styling the application (via `style.css`).
- **JavaScript**: For handling the API requests and DOM manipulation (via `script.js`).
- **Font Awesome**: For the magnifying glass icon used in the search button.

## Project Structure
```
project-root/
│
├── index.html      # The main HTML file
├── style.css       # The CSS file for styling (should be in the same directory)
├── script.js       # The JavaScript file for functionality (should be in the same directory)
├── weather-color-sun-cloud-svgrepo-com.svg  # Favicon for the application
```

## Usage

1. **Enter City Name**: Type the name of the city in the input field labeled "Enter City".
2. **Search Weather**: Click on the search button (magnifying glass icon) to fetch the weather data.
3. **View Weather Information**: The application will display the city name, temperature, and a brief weather description, along with an icon representing the current weather.

## Dependencies
- **Font Awesome**: The application uses Font Awesome for the search button icon. The library is linked via a CDN.

## Setup Instructions

1. Clone the repository or download the project files.
2. Ensure that the `index.html`, `style.css`, `script.js`, and `weather-color-sun-cloud-svgrepo-com.svg` files are in the same directory.
3. Open `index.html` in a web browser to run the application.

## Future Enhancements
- Add error handling for invalid city names.
- Improve the user interface with additional styling.
- Display more weather information, such as wind speed, humidity, etc.
- Add responsiveness to ensure the app works well on mobile devices.

## License
This project is open-source and available under the [MIT License](LICENSE).
