# Sun Position Calculator

The Sun Position Calculator is a web-based application designed to provide real-time solar data based on the user's geographical location. By utilizing HTML, Tailwind CSS for styling, and JavaScript with the SunCalc library, it calculates and displays solar azimuth, solar altitude, solar noon, sunrise, sunset times, and the day's length.

**Live Demo**: [Sun Position Calculator](https://battlefeel1942.github.io/sun-position-calculator/)

## Features

- **Real-Time Solar Data**: Updates solar position data every second.
- **Geolocation Support**: Automatically fetches the user's current location to display relevant solar data.
- **Responsive Design**: Adapts layout for different screen sizes, ensuring a seamless experience across devices.
- **Error Handling**: Provides user feedback if geolocation services are unavailable or permission is denied.
- **URL Parameters**: Allows specifying latitude and longitude through URL parameters for immediate data display without user interaction.

## Technologies Used

- **HTML**: Structures the web page and its content.
- **Tailwind CSS**: A utility-first CSS framework used for styling and responsive design.
- **JavaScript**: Powers the application's logic, including fetching user location and calculating solar data.
- **SunCalc Library**: A small JavaScript library for calculating the position of the sun and moon.

## Setup

To run this project locally:

1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser.

No additional setup or dependencies are required.

## Usage

Upon loading the application, click the **Get My Location** button to fetch your current geographical location. The application will then display the following solar data:

- Latitude and Longitude
- Solar Azimuth and Altitude
- Solar Noon
- Sunrise and Sunset times
- Day Length

For advanced users, latitude and longitude can be specified directly as URL parameters (e.g., `?lat=48.8584&lon=2.2945`) to bypass the geolocation step.

## Contributing

Contributions to the Sun Position Calculator are welcome! If you have suggestions for improvements or new features, feel free to fork the repository, make changes, and submit a pull request.

## Credits

This project makes use of the following libraries and resources:

- **Tailwind CSS**: A utility-first CSS framework used for styling. For more information, visit [Tailwind CSS](https://tailwindcss.com/).
- **SunCalc Library**: A small JavaScript library for calculating sun and moon positions and phases. Developed by Vladimir Agafonkin. For more information or to contribute, visit [SunCalc on GitHub](https://github.com/mourner/suncalc).

Special thanks to the developers and contributors of these libraries for making them available and supporting the open-source community.

## License

This project is open source and available under the [MIT License](LICENSE).
