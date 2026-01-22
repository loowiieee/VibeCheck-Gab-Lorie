This project is a simple Node.js and Express-based API with a frontend button interface developed for CPE 411L Activity #3. The backend runs on localhost and provides multiple API endpoints that return JSON responses, including fortune, joke, mood-based vibe, smash counter, and a secret endpoint. The frontend consists of an HTML page with JavaScript that uses fetch to call these endpoints and display the returned data on screen when buttons are clicked. This activity demonstrates basic server setup, API route creation, frontend–backend communication, and proper GitHub workflow using feature branches, meaningful commits, pull requests, and merges.



How to Run Locally:

Install dependencies: npm install
Start the server: node server.js
Open index.html in a browser
API runs at http://localhost:3000


API Endpoints:

GET /api/fortune – Get a random fortune
GET /api/joke – Get a random joke
GET /api/vibe?mood=happy|tired|stressed – Get mood-based response
POST /api/smash – Increment smash counter
GET /api/smashes – Get current smash count
GET /api/secret?code=411L – Access secret message
