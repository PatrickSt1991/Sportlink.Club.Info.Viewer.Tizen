# Sportlink.Club.Info.Viewer.Tizen

## Overview
Welcome to the Sportlink Club Info Viewer Tizen! This project showcases match results, match information, and pre-match details using a modern Vue 3 + Vite application. Additionally, it includes a Tizen app designed for older Samsung Smart TVs, making sports data accessible to a wider audience.

## Required Reading 
[Read for usage and setup of Build and Tizen App for full explanation](https://patrickst1991.github.io/Sportlink.Club.Info.Viewer/)

This repository contains a build versions of the [Sportlink.Club.Info.Viewer repository](https://github.com/PatrickSt1991/Sportlink.Club.Info.Viewer).
If you're device is new enough to run the code on it's own then you probably won't be needing this.

Adjust config.xml to your own needs.

## Features
 - Dynamic Match Results: Displays real-time match results for various sports.
 - Match Information: Provides detailed information about ongoing and upcoming matches.
 - Pre-Match Insights: Offers insights and statistics before the match begins.
 - Tizen Support: Includes an app for older Samsung Smart TVs, ensuring accessibility for all users.

## Technologies
 - Frontend:
   - Vue 3
   - Vite
 - Tizen App:
   - Tizen Studio
   - Samsung Smart TV SDK

## Installation
## Vue 3 + Vite App
 1. Clone the repository:
    ```
    git clone https://github.com/PatrickSt1991/Sportlink.Club.Info.Viewer.git
    cd /Sportlink.Club.Info.Viewer
    ```
 2. Install dependencies:
    ```npm install```
 3. Start the development server:
    ```
    npm run dev
    npm run build
    ```
    
 5. Open your browser and navigate to http://localhost:5173 **(or the specified port in the terminal)** to see the app in action!
 6. Change the settings in config.js
    - BASE_URL = './'; - Keep as is for Tizen app
    - CLIENT_ID = ''; - Fill with your own ClientId
    - PROGRAMMA_DAGEN = '7'; - Used for MatchInfo, shows the amount of days ahead for upcomming matches
    - UITSLAG_DAGEN = '7'; - Used for MatchResults, shows the amount of days in the past for match results
    - PREMATCH_REFRESH = '15'; - Amount of minutes to refresh the /prematch-info screen
    - ENABLE_SCREEN_SWITCH = true; - Is it allowd to switch between /match-info and /match-results
    - HOMESCREEN -> Used for what screen should be shown at start-up

## Tizen Samsung TV App
 1. Install Tizen Studio and set up your environment.
 2. Clone the Tizen app directory from this repository.
    `git clone https://github.com/PatrickSt1991/Sportlink.Club.Info.Viewer.Tizen.git
    cd /Sportlink.Club.Info.Viewer.Tizen`
 3. Open the Tizen project in Tizen Studio or Visual Studio with the Tizen Extension.
 4. Connect your Samsung Smart TV to your development environment.
 5. Build and deploy the app to your Samsung Smart TV.

## Usage
Once the app is running, you can:

 - View live match results and statistics.
 - Access detailed match information by selecting a match.
 - Check pre-match insights to get ready for upcoming games.

## Tizen Samsung TV App
The Tizen Samsung TV app is designed to provide match results and information on older Samsung Smart TVs. Follow the steps in the Installation section to set up and deploy the app.

## Features of the Tizen App
 - Simple and intuitive user interface.
 - Real-time updates for match results.
 - Accessible information for sports enthusiasts on older TV models.

## Contributing
I welcome contributions to improve the Sportlink Club Info Viewer! If you would like to contribute, please follow these steps:

 1. Fork the repository.
 2. Create a new branch (git checkout -b feature-YourFeature).
 3. Make your changes and commit them (git commit -m 'Add YourFeature').
 4. Push to the branch (git push origin feature-YourFeature).
 5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/PatrickSt1991/Sportlink.Club.Info.Viewer.Tizen/blob/main/LICENSE) file for details.
