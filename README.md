
# Country Information App

This is a simple React app that allows you to search for information about countries. You can search for a country by name, and the app will display details such as population, capital, languages spoken, and weather information for the capital city.

## Features

- Search for countries by name.
- View detailed information about a specific country.
- Get real-time weather information for the capital city of the selected country.
- Responsive and user-friendly design.

## Technologies Used

- React.js
- Axios for making API requests
- Tailwind CSS for styling

## Setup

To run this app locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/country-information-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd country-information-app
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add your OpenWeatherMap API key as follows:

   ```plaintext
   VITE_API_KEY=your_openweathermap_api_key
   ```

   Replace `your_openweathermap_api_key` with your actual API key.

5. Start the development server:

   ```bash
   npm start
   ```

6. Open your browser and access the app at [http://localhost:3000](http://localhost:3000).

## Usage

- Enter a country name in the search bar and press Enter or click the "Search" button.
- Click the "Show" button next to a country to view detailed information, including weather data.

## Acknowledgments

- Data for countries is fetched from the [Restcountries API](https://restcountries.com/).
- Weather information is provided by the [OpenWeatherMap API](https://openweathermap.org/).

## Author

- Your Name

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README file with additional information or sections as needed for your specific project. Make sure to replace placeholders with actual details, such as your API key, author name, and license information.
