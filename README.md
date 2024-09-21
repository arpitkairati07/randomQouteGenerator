Random Quote Generator
This is a simple Random Quote Generator web application built using React.js. The app fetches a random piece of advice from the Advice Slip API and displays it on the screen. Users can generate new quotes by clicking a button, and the background has a visually appealing gradient overlay on an image.

Features
Fetches random quotes from the Advice Slip API.
Displays the quote in a card with a button to fetch a new random quote.
Responsive design with a centered card on a background image.
Background image has a linear gradient overlay.
Uses axios to handle API requests.

 Install Dependencies
Make sure you have Node.js and npm installed. Then, install the required dependencies.

bash
Copy code
npm install


Usage
When you first open the app, a random quote will be displayed. To get a new random quote, simply click the "Give Me Advice" button. The app will fetch a new quote from the API and display it in the center of the screen.

Folder Structure
bash
Copy code
random-quote-generator/
├── public/
│   ├── index.html
│   └── src/
│       ├── App.js
│       ├── App.css
│       └── index.js
├── package.json
├── README.md
└── .gitignore
Technologies Used
React.js: A JavaScript library for building user interfaces.
Axios: Promise-based HTTP client for making API requests.
CSS: For styling the layout and components.
Advice Slip API: Public API providing random pieces of advice.