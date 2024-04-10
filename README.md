# Journey Journal 📖✈️

Welcome to Journey Journal, the ultimate mobile app for documenting your travel experiences and creating lasting memories! 🌍💫

## What is Journey Journal? 🤔

Journey Journal is a powerful tool designed for tourists, holiday goers, and anyone who wants a fast and intuitive way to capture their adventures on the go. With Journey Journal, you can easily document your memories and experiences, all within a user-friendly mobile application. 📱✨

### This app was created by our team "Work from Ho Ho Home" as part of our final project at Northcoders Bootcamp -> [presentation](https://northcoders.com/projects/nov-2022/journey-journal)


## Features ✨

- 🗺️ Create personalized Journey cards for each trip
- 📅 Add trip details including Name, City, and start/end dates
- 🏨 Document specific places visited during the trip, categorized into Accommodation, Catering, and Attractions
- 📝 Capture details for each place, such as Name, City, Address, Description, Rating, and date
- 💡 Get personalized suggestions for places to visit based on your location
- 💾 Store your memories securely and access them anytime, anywhere

## Demo 🎥

Check out the demo gif to see Journey Journal in action:

![Journey Journal Demo](assets/Demo.gif)

## Technologies Used 🛠️

Journey Journal is built using the following technologies:

- ⚛️ React Native
- 🚀 Expo
- 🔥 Firebase
- 📜 React Native Paper

## APIs 🌐

Journey Journal integrates with the following APIs to enhance your travel experience:

- 🌍 Geoapify
- 🎟️ Ticketmaster

In order to access this repo locally, you can either fork and clone this repo, or clone directly from the following url:

```
git clone https://github.com/harpreet-singh-147/Journey-Journal-App.git
```

Firstly, please run npm install to install dependencies.

In order to run this repo on your local machine you will need to download and install the [Android Studio Emulator](https://developer.android.com/studio) or the [XCode Iphone Emulator](https://developer.apple.com/xcode/) (if using macOS).

You will also need to create a [Google](https://www.google.com/account/about/) account then get started with [Firebase](https://cloud.google.com/firestore/docs/client/get-firebase), register a new API Key at [Ticketmaster](https://developer-acct.ticketmaster.com/user/register) and [geoapify.com](https://www.geoapify.com/), then add your own config files to a newly created .env file. The .env file should look like below:

```
FIREBASE_API_KEY=*Your Firebase config details here*
FIREBASE_AUTH_DOMAIN=*Your Firebase config details here*
FIREBASE_PROJECT_ID=*Your Firebase config details here*
FIREBASE_STORAGE_BUCKETt=*Your Firebase config details here*
FIREBASE_MESSAGING_SENDER_ID=*Your Firebase config details here*
FIREBASE_APP_ID=1:*Your Firebase config details here*
TICKETMASTER_API=*Your ticketmaster API key here*
GEOPIFY_API_KEY=*Your geopify API key here*
```

