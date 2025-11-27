Know Weather
i. Setup Steps

Clone or Download the Project

Download the ZIP or clone the repository using

git clone <repo-url>


Open the Project Folder

Ensure the files index.html, style.css, and script.js are present.

Get an API Key

Visit OpenWeatherMap (https://openweathermap.org/
)

Create a free account

Navigate to: API Keys → Generate an API key

Copy the key.

Add Your API Key

Open script.js

Replace the placeholder key:

const API_KEY = "YOUR_API_KEY";


Run the App

Simply open index.html in any web browser
OR
Use Live Server (VS Code Extension):

Right-click → Open with Live Server

Search for a City

Type a city name

Click Search or press Enter.

ii. Tech Stack Used
Frontend

HTML5 – Page structure

CSS3 – Styling + responsive UI

JavaScript (Vanilla JS) – API calls, DOM updates

API

OpenWeatherMap API – Fetching real-time weather data

Tools

VS Code

Live Server (optional)

Git & GitHub (optional for version control)
iii. Screenshots or Short Screen Recording
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/6fc9b637-7113-4afd-9988-3bd44ac7c386" />

<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/03efad65-e900-48a8-b227-508f10369f79" />



iv. Assumptions & Bonus Features Implemented
Assumptions

The user will enter a valid city name in English.

Network connection will be available for API calls.

OpenWeather API returns consistent JSON data structure.

Bonus Features (Optional to Include)

You can mention whichever you actually implemented:

🔄 Auto-detect Location Weather using Geolocation API

🌡️ Temperature Unit Toggle (°C / °F)

🎨 Dynamic Backgrounds based on weather (sunny, cloudy, rainy, etc.)

💾 Search History stored in localStorage

⚠️ Custom Error Handling for invalid cities or API failures

🌙 Dark / Light Theme Toggle

⏳ Loading Spinner when fetching data

📱 Fully Responsive UI for mobile devices
