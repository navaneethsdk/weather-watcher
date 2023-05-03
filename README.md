# Weather Watcher Assessment

## Introduction

Welcome to the React onboarding assessment! This assessment is designed to
evaluate your proficiency in React and web development. You will be given a
React application called `Weather Watcher`, which has three parts:

1. A form that accepts latitude and longitude inputs and displays weather
   details like temperature, humidity, and wind speed.
2. A section that displays the current location of the user based on their
   browser location.
3. A table that lists popular cities in India with their latitude and longitude,
   along with a search filter to search for cities by name.

Your task is to modify the `Weather Watcher` application by implementing the
above three parts. Refer to
[this](https://app.usebubbles.com/uHuHmRcy1bBCZTh131h3eJ/weather-watcher) video
to get a better understanding of the application. 

**Ensure you read the entire
document before proceeding with the assessment.**

## Getting started

### Clone the repository

Clone the repository by running the following command in your terminal:

```
git clone git@github.com:navaneethsdk/weather-watcher.git
```

### Install Dependencies

Navigate into the project directory and install the dependencies by running the
following command:

```
cd weather-watcher
yarn install
```

### Running the Application

To run the application, use the following command:

```
yarn start
```

This will start the development server and open the application in your default
browser at `http://localhost:3000`.

## Folder Structure

The repository contains the following files and folders:

- `public`: contains the HTML file that is served to the browser
- `src`: contains the React application
  - `components`: contains all React components used in the application
  - `App.jsx`: the main component that renders the entire application
  - `index.js`: the entry point for the React application

You should only modify the files in the `src` folder.

## OpenWeatherMap API

You will need to obtain an API key from OpenWeatherMap to fetch weather data.
You can obtain an API key by creating an account on
[OpenWeatherMap](https://openweathermap.org/) and navigating to the
[API Keys](https://home.openweathermap.org/api_keys) tab in your account
dashboard. Once you have obtained an API key, create a `.env` file in the root
of the project and add the following line with your API key:

```
REACT_APP_API_KEY=<your_api_key_here>
```

This file is ignored by git and will not be committed to the repository.

To access the weather data, you may use the `Current weather data` API which
provides various weather-related data for a given latitude and longitude. Here's
the link to the API documentation: https://openweathermap.org/current

## Logistics

To get started with this assessment, please follow the instructions below:

- Clone this repository to your local machine.
- Create a private repository in your account with the name
  `weather-watcher-by-<your name>` and upload the same repo content into it.
  Invite `@yedhink` and `@navaneethsdk` as collaborators in your repository.
- Make sure to start with a clean commit history. You should not include any of
  the commits made to this repository in your submission.
- Do not merge your changes directly into the `main` branch. Instead, create a
  pull request from your feature branch to `main`.
- Use the `squash and merge` option when merging your pull request. This will
  keep the commit history clean and make it easier for us to review your
  changes. Refer to
  [this](https://handbook.neetokb.com/articles/git-and-github-essentials) guide
  for more information.
- Use the GitHub issues feature to track your progress and report any bugs or
  issues you encounter. Before making your changes, make sure to create an
  `epic`-labeled issue and corresponding sub-issues rather than randomly making
  PRs. Refer to
  [this](https://handbook.neetokb.com/articles/tracking-issues-using-milestones-in-github)
  guide for more information on how to use issues and milestones.
- You will have a total of 1 day to complete this assessment.
- You are allowed to use any resources you would normally use when developing,
  such as online documentation and Google.
- The assessment will be evaluated based on the following criteria:
  1. Code quality
  2. Functionality
  3. Best practices
- Candidates need not put much effort into improving the aesthetics of the app.
- Candidates should not share the code or the API key with anyone else.
- Candidates should not plagiarize or copy code from other sources.
- Once you have completed the assessment, please create an issue in your
  repository mentioning `@yedhink` and `@navaneethsdk` to review it.

## Conclusion

We hope this README file helps you get started with the `Weather Watcher`
assessment. If you have any questions or encounter any issues while working on
this assessment, please post a message in the corresponding Slack channel to
which you've been added as part of the orientation. If you haven't yet been
added to such a channel, please contact `@yedhink`. Good luck with your
assessment!
