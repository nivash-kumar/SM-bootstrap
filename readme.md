Multi-Agency Mission Tracker
A simple, interactive web application to browse space missions from different agencies like ISRO, NASA, and SpaceX. This project is built with Bootstrap 5 and vanilla JavaScript and uses the Google Gemini API to generate fun facts and explanations about the missions.

✨ Features
Agency Selection: View missions from ISRO, NASA, and SpaceX from a dropdown menu.

Dynamic Filtering: Filter missions by their type (e.g., Lunar, Planetary, Human Spaceflight).

Interactive Cards: Each mission is displayed on a clean, responsive Bootstrap card.

AI-Powered Facts: Click the "Fun Facts" button to open a modal and get interesting, AI-generated trivia about the selected mission.

Tech Explanations: Inside the modal, get simple explanations for the mission's launch vehicle and orbit type.

Responsive Design: The layout adapts smoothly to desktop, tablet, and mobile screens.

🛠️ Tech Stack
Frontend: HTML5, Bootstrap 5, CSS3

JavaScript: Vanilla JavaScript (ES6+)

API: Google Gemini API

🚀 Getting Started
No complex build steps are required to run this project.

Prerequisites
You will need a modern web browser and a Google Gemini API Key.

JavaScript

const apiKey = "AIzaSyCq1xy_IjQ0SEW9xa5cz2kti44n4uFuxoA"; // Replace with your key
Replace the placeholder key with your own Google Gemini API key. You can get one from Google AI Studio.

Open in Browser:
Simply open the index.html file in your web browser to run the application.

🔧 How It Works
The application is contained within a single index.html file for simplicity.

missionData Object: Mission information (name, type, vehicle, etc.) is stored in a static JavaScript object at the top of the script block. This acts as a local database.

renderMissions(): This function dynamically creates Bootstrap cards for each mission based on the currently selected agency and filter.

callGemini() Function: When a user clicks "Fun Facts" or "Explain the Tech", a prompt is constructed and sent to the Google Gemini API via this async function.

Bootstrap Modal: The response from the API is then displayed in a Bootstrap modal component, which is controlled entirely by Bootstrap's JavaScript API.
