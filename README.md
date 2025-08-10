# Multi-Agency Mission Tracker

A simple, interactive web application to browse space missions from different agencies like ISRO, NASA, and SpaceX. This project is built with **Tailwind CSS** and **vanilla JavaScript** and uses the **Google Gemini API** to generate fun facts and explanations about the missions.

## ✨ Features

* **Agency Selection**: View missions from ISRO, NASA, and SpaceX from a dropdown menu.
* **Dynamic Filtering**: Filter missions by their type (e.g., Lunar, Planetary, Human Spaceflight).
* **Interactive Cards**: Each mission is displayed on a clean, responsive card with hover effects.
* **AI-Powered Facts**: Click the "Fun Facts" button to open a modal and get interesting, AI-generated trivia about the selected mission.
* **Tech Explanations**: Inside the modal, get simple explanations for the mission's launch vehicle and orbit type.
* **Responsive Design**: The layout adapts smoothly to desktop, tablet, and mobile screens using Tailwind's responsive prefixes.

## 🔗 Links

* **Live Demo**: [your-hosting-link.com](https://your-hosting-link.com)
* **Figma Design**: [Figma Project Link]([https://www.figma.com/file/your-figma-project-id](https://www.figma.com/design/kgXwmRcBuahEwEbim8gxJq/mission-tracker-UI?node-id=51-421&t=NopEVVDTs7FhWnDd-1))

## 🛠️ Tech Stack

* **Frontend**: HTML5, Tailwind CSS
* **JavaScript**: Vanilla JavaScript (ES6+)
* **API**: Google Gemini API

## 🚀 Getting Started

No complex build steps are required to run this project since it uses the Tailwind CSS CDN.

### Prerequisites

You will need a modern web browser and a **Google Gemini API Key**.

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/nivash-kumar/SM-bootstrap.git](https://github.com/nivash-kumar/SM-bootstrap.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd mission-tracker
    ```
3.  **Add your API Key:**
    Open the `index.html` file and find the following line within the `<script>` tag at the bottom:
    ```javascript
    const apiKey = "AIzaSyCq1xy_IjQ0SEW9xa5cz2kti44n4uFuxoA"; // Replace with your key
    ```
    Replace the placeholder key with your own Google Gemini API key. You can get one from [Google AI Studio](https://aistudio.google.com/app/apikey).

4.  **Open in Browser:**
    Simply open the `index.html` file in your web browser to run the application.

## 🔧 How It Works

The application is contained within a single `index.html` file for simplicity.

* **Styling**: The UI is styled directly in the HTML using **Tailwind CSS utility classes**. This allows for rapid and responsive design without writing separate CSS files.
* **`missionData` Object**: Mission information is stored in a static JavaScript object that acts as a local database.
* **`renderMissions()`**: This function dynamically creates the mission cards based on the currently selected agency and filter.
* **Custom Modal**: The "Fun Facts" modal is a custom component built with HTML and styled with Tailwind CSS. Its visibility and animations are controlled with JavaScript by adding and removing classes.
* **`callGemini()` Function**: When a user clicks a button, a prompt is constructed and sent to the Google Gemini API via this `async` function to fetch dynamic content.

## 📜 License

This project is intership project .

## 👦 About Me
