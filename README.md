# BoredBot 🤖

BoredBot is a simple JavaScript project that suggests random activities when you're bored. It fetches activity suggestions from an API and dynamically updates the webpage when you click a button.

## ✨ Features

- Fetches random activity suggestions from the Scrimba Bored API.
- Dynamically displays the suggested activity on the webpage.
- Updates the page title after an activity is loaded.
- Changes the background styling for a more interactive experience.

## 🛠️ Built With

- HTML5
- CSS3
- JavaScript
- [Vite](https://vite.dev/)
- [Scrimba Bored API](https://apis.scrimba.com/bored/api/activity)

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- npm

### Installation

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL displayed in your terminal.

### Production Build

To create a production build, run:

```bash
npm run build
```

To preview the production build locally, run:

```bash
npm run preview
```

## ⚙️ How It Works

1. The user clicks the activity button.
2. JavaScript triggers a function that sends a request to the Bored API.
3. The API response is converted into JSON.
4. The returned activity is displayed dynamically on the webpage.
5. The page title and background styling are updated.

## 📂 Project Structure

```text
├── index.html       # HTML structure
├── index.css        # Styling and layout
├── index.js         # JavaScript logic and API requests
├── notes.md         # Learning notes
├── package.json     # Dependencies and scripts
└── vite.config.js   # Vite configuration
```

## 📚 Concepts Practiced

- Fetch API and HTTP requests
- Promises and `.then()` callbacks
- Working with JSON data
- DOM manipulation
- Event listeners
- Dynamic content updates
- Basic frontend development workflow

## 🔮 Possible Improvements

- Add loading feedback while fetching an activity.
- Handle API errors gracefully.
- Add an option to fetch another activity.
- Improve accessibility and responsive design.

## 🎯 Purpose

Built as a learning project to practise JavaScript fundamentals, asynchronous programming, API integration, and DOM manipulation.
