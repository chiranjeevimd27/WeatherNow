**Weather Now App**

**Description**
The **Weather Now** application allows users to check the current weather conditions for any city. The app displays information such as temperature, wind speed, humidity, and a brief description of the weather (e.g., sunny, rainy, cloudy). Users can search for multiple cities and view real-time weather updates using the **Open-Meteo API**.

**Features**
- **City Search**: Input a city name to view current weather data.
- **Weather Display**: Shows temperature, wind speed, and humidity.
- **Weather Description**: Provides a simple description (e.g., sunny, cloudy).
- **Responsive Design**: Works well on both desktop and mobile devices.
- **Error Handling**: Gracefully handles errors like no city found or API issues.

**Tech Stack**
- **Frontend**: React.js
- **API**: Open-Meteo API
- **Styling**: Basic CSS (or Tailwind CSS if preferred)
- **State Management**: React State
- **HTTP Requests**: Axios

**Setup Instructions**

**Prerequisites**
Ensure you have the following installed:
- **Node.js** (for local development, if needed)
- **npm** or **yarn** (for dependency management)

**Installing Dependencies**
1. Clone the repository:

   ```bash
   git clone https://github.com/username/weather-now-app.git
   ```

2. Navigate to the project folder:

   ```bash
   cd weather-now-app
   ```

3. Install dependencies using npm:

   ```bash
   npm install
   ```

   Or using yarn:

   ```bash
   yarn install
   ```

**Running the Application Locally**
1. Start the application:

   ```bash
   npm start
   ```

2. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

**Usage**

1. Open the application in your browser.
2. Enter the name of a city in the input field.
3. Click the **Search** button to see the current weather information.
4. The weather data includes temperature, wind speed, humidity, and a brief description of the weather.

**Deployed Application**

You can view the live version of the app here:

[Weather Now App - StackBlitz](https://stackblitz.com/edit/weather-now-app)


**Contributing**

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature/your-feature-name`).
5. Create a pull request.

**License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Acknowledgements**
- The **Open-Meteo API** for providing weather data.
- **StackBlitz** for online development and hosting.
