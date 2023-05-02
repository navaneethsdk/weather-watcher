# Weather Watcher Assessment

## Introduction

Welcome to the React onboarding assessment! This assessment is designed to evaluate your proficiency in React and web development. You will be given a React application called `Weather Watcher`, which has three parts:

1. A form that accepts latitude and longitude inputs and displays weather details like temperature, humidity, and wind speed.
2. A section that displays the current location of the user based on their browser location.
3. A table that lists popular cities in India with their latitude and longitude, along with a search filter to search for cities by name.

Your task is to modify the `Weather Watcher` application by implementing the above three parts.

## Getting started

### Clone the repository

Clone the repository by running the following command in your terminal:

```
git clone https://github.com/navaneethsdk/weather-watcher.git
```

### Install Dependencies

Navigate into the project directory and install the dependencies by running the following command:

```
cd weather-watcher-assessment
npm install
```

### Running the Application

To run the application, use the following command:

```
npm start
```

This will start the development server and open the application in your default browser at `http://localhost:3000`.

## Folder Structure

The repository contains the following files and folders:

- `public`: contains the HTML file that is served to the browser
- `src`: contains the React application
  - `components`: contains all React components used in the application
  - `App.jsx`: the main component that renders the entire application
  - `index.js`: the entry point for the React application

You should only modify the files in the `src` folder.

## OpenWeatherMap API

You will need to obtain an API key from OpenWeatherMap to fetch weather data. You can obtain an API key by creating an account on [OpenWeatherMap](https://openweathermap.org/) and navigating to the [API Keys](https://home.openweathermap.org/api_keys) tab in your account dashboard. Once you have obtained an API key, create a `.env` file in the root of the project and add the following line with your API key:

```
REACT_APP_API_KEY=<your_api_key_here>
```

This file is ignored by git and will not be committed to the repository.

To access the weather data, you may use the `Current weather data` API which provides various weather-related data for a given latitude and longitude. Here's the link to the API documentation: https://openweathermap.org/current

## Logistics

- You will have a total of 1 day to complete this assessment.
- You are allowed to use any resources you would normally use when developing, such as online documentation and Google.
- The assessment will be evaluated based on the following criteria:
  1. Code quality
  2. Functionality
  3. Best practices
- Candidates need not put much effort into improving the aesthetics of the app.
- The candidate should not share the code or the API key with anyone else.
- The candidate should not plagiarize or copy code from other sources.
- Once you have completed the assessment, please create an issue mentioning `@yedhink` and `@navaneethsdk` to review it.

## Conclusion

We hope this README file helps you get started with the `Weather Watcher` assessment. If you have any questions or need further assistance, please feel free to contact us. Good luck with your assessment!
