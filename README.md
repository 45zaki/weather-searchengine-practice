🌦️ **Live Weather Search Engine:**
A modern live weather search application built using HTML, CSS, and JavaScript, powered by the SheCodes Weather API.
Users can search for any city and view real-time weather information.

🚀 **Features:**
- Search weather by city name
- Real-time temperature display
- Shows current date and day of the week
- Wind speed information
- Humidity level
- City name and weather description
- Live API-based updates
- Clean and responsive UI

🛠️ **Technologies Used:**
- HTML5 – Page structure
- CSS3 – Styling and layout
- JavaScript (ES6) – Logic and DOM manipulation
- Axios – HTTP requests
- SheCodes Weather API – Live weather data

📸 **Preview**
<img width="1556" height="976" alt="53686" src="https://github.com/user-attachments/assets/a3d4f804-a08e-42d6-a780-a2fa843eb8c8" />


📂 **Project Structure:**

- `index.html`
- `style.css`
- `index.js`

⚙️ **How It Works:**
1. The user enters a city name
2. JavaScript sends a request to the SheCodes Weather API
3. The API returns live weather data:
  - Temperature
  - Date & weekday
  - Weather description
  - Wind speed
  - Humidity
4.The UI updates dynamically without reloading the page

⏰ **Timezone Limitation:**
- The date and time displayed in this application are based on the user’s local timezone.
- The free SheCodes Weather API does not provide timezone information for searched cities.
- As a result, JavaScript converts the API timestamp to the browser’s local time instead of the city’s local time.
- Displaying city-specific local time would require an API that includes timezone offsets or a separate timezone service.

🔑 **API Setup:**
This project uses the SheCodes Weather API.
In script.js, replace YOUR_API_KEY with your own key:
const apiKey = "YOUR_API_KEY";

▶️ **How to Run the Project:**
Clone the repository:
git clone https://github.com/45zaki/weather-searchengine-practice.git
Open index.html in your browser
-No installation or build tools required

📌 **Future Improvements:**
Current location weather (Geolocation API)
Multi-day weather forecast
City-local timezone support
Dark mode
Enhanced mobile responsiveness

📄 **License:**
This project is open-source and intended for learning and educational purposes.

🙌 **Acknowledgments:**
- **SheCodes** for the Weather API and for their mission to support and empower women in learning and building careers in technology.
- Inspired by real-world weather applications.
