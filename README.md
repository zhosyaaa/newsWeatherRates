# neWs Web Application

neWs is a web application that provides information about weather, currency conversion, and top headlines. The application is built using Node.js, Express, and integrates with external APIs for weather data, currency conversion, and news articles.


## Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/neWs.git

2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Start the server using `nodemon root.js`.

## Usage
- The server runs on port 3000.
- Access the weather in a web browser via the link `http://localhost:3000/weather`.
- Calculate the dollar exchange rate for any other currency using the link `http://localhost:3000/currency`.

## Dependencies
- **Express:** Used for server setup and routing.
- **Body-parser:** Middleware for parsing incoming request bodies.
- **Axios:** Handles HTTP requests.
- **Path:** Helps manage file paths.
- **Nodemon** Monitors for changes and automatically restarts the server.

## APIs Used
- OpenWeatherMap API - For weather data.
- News API - For top headlines news articles.
- ExchangeRate-API - For currency conversion.

## Running the Server
The server script is located in `root.js`. Start the server using `nodemon root.js`.

## File Structure
- `views/`: Contains client-side files (HTML, CSS, JS).
- `routes/`: Server-side routes for request handling.
- `bmiData.json`: Stores historical BMI calculation data.
