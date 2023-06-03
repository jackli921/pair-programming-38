## AI Weather-Clothing Advisory
Input your current location, and get your suggestion for what to dress! 

## Overview
This project was born out of my first week-long pair programming session organized by Chingus. The purpose was to utilize current weather data in combination with LLMs such as ChatGPT to get advice on what to dress given the current weather. The challenges lied in connecting all logic for passing data between front and backend, especially:
- Making call to get the open weather API key from the backend.
- Making call to open weather to get the weather data.
- Making call to OpenAI model with weather data for a response.

## Features
1. One search box for user input with automatic input validation.
2. City list of 300+ choices of cities to choose or scroll from.
3. A 2-3 sentence summary suggestion and suggestions in bullet points.

## Installation
To run this project locally:

1. Clone this project locally.
2. Open the root directory, add a .env file.
3. Add your own OpenAI and OpenWeather API Keys and save.
4. Open your terminal and navigate into the root directory.
5. Run npm install to install dependencies for the backend.
6. Run node index.js to start the backend server.
7. Open another terminal, navigate into the Client folder.
8. Run npm install to install dependencies for the frontend.
9. Run npm run dev to build the frontend project.

## Dependencies
- ReactJS

## Technologies
- ReactJS, CSS3

## Improvements
- Convert to TypeScript.
- Improve responsiveness on mobile devices.
