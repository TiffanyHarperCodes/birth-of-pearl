# Birth of Pearl - An App for Oyster Lovers
## Overview

Users can search oysters by specific locations and retrieve oyster profiles.
Users also receive a random fact about oysters upon app load. <br>
Originally created as a Capstone Project at [Ada Developers Academy](https://adadevelopersacademy.org/) — now being independently rebuilt with a real database, enhanced features, and an AI-powered oyster sommelier.

#### V2 — Coming Soon

<img src="/Images/Welcome.png" alt="Welcome" width="250" height="500">.  <img src="/Images/AboutUs.png" alt="About Us" width="250" height="500">. <img src="/Images/RandomFact.png" alt="Random Fact" width="250" height="500">.  <img src="/Images/RegionSearch.png" alt="Regional Search" width="250" height="500">.  <img src="/Images/LocationSearch.png" alt="Location Search" width="250" height="500">. <img src="/Images/Profile.png" alt="Oyster Profile" width="250" height="500">

## App Features

- **Tappable Image** on Welcome screen for one-touch search.
- **Swipeable Fact Card** displays a random oyster fact on app load — built with React Native's built-in `PanResponder` and `Animated` APIs. Works on both iOS and Android.
- **Buttons** to navigate search based on region and location.
- Random oyster facts are sourced from a curated local dataset bundled with the app.


## Requirements
- Node.js - this is needed in order to access the Node Package Manager (npm).


## Installation/Environment Set-Up

- Clone this repository.
- Install dependencies by running `npm install`.
- To run the app locally, use `npx expo start`.
- To test the app on your personal device:
  - Download **Expo Go** for [iOS](https://apps.apple.com/us/app/expo-go/id982107779) or [Android](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=en&gl=US).
  - Scan the QR code displayed in your terminal after running `npx expo start`.
- To test on a simulator/emulator on your local machine:
  - For an iPhone Simulator: Download [Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) and follow the setup instructions.
  - For an Android Emulator: Download [Android Studio](https://developer.android.com/studio) and follow the setup instructions.
- Currently, the database is small and therefore stored in a **JSON file**. This application is not leveraging a backend storage solution at this time.
