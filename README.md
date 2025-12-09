# Location-Based Event Invitation & Social Mobile Application

This location-based social media application allows users to share, discover, and join events based on their geolocation. The app aims to increase social interactions, help users meet new people, and facilitate fun experiences through a mobile platform.

## Project Purpose
The primary objective of this project is to create a platform where people can share, discover, and participate in location-based events. This platform enables users to engage in social interactions, encourages meeting new people, and provides entertaining experiences. Additionally, it enriches the user experience with features like a personality test, allowing users to join events that match their specific personality traits.

## Project Overview
The project is realized through a mobile application. It enables users to share their location-based events, join other events, and discover activities near their location. Users can also access private chat rooms to discuss events and communicate with other attendees. 

The application features an integrated **Big 5 Personality Test** to evaluate users' personality traits. Based on these test results, the system allows users to join events suitable for their personalities. This ensures that users have the chance to participate in more compatible events with people who share similar personality traits. The app targets increasing social interactions, establishing new connections, and providing fun experiences.

## Key Features

1. **Event Sharing:** Users can create their own events and share them with others. The application includes details such as location, time, event descriptions, and information for attendees.
2. **Event Discovery:** Users can view nearby events on a map based on their location. They can use filter settings to sort events by date, category, or popularity, providing ease of use.
3. **Private Chat Rooms:** A private chat is created for each event. Users can join these chats if they wish. In these rooms, participants can communicate about the event, exchange information, coordinate plans, and socialize.
4. **Big 5 Personality Test:** A distinctive feature of the app is the Big 5 Personality Test. Users can evaluate their personality traits, and based on the results, the app presents recommended actions or events for them to choose from.
5. **User Profile:** Users can create personal profiles within the app to share their interests, event history, and social networks.

## Technical Details

1. **Platform:** Developed using **Java** in Android Studio.
2. **Location Services:** Location-based features are provided via **Google Maps API** integration.
   > *Note: This API key has been restricted for security reasons. To run the app locally, you need to obtain a key from cloud.google.com and enter it into the `AndroidManifest.xml` file.*
3. **Database:** **Firebase Realtime Database** is used for user information and event data.
4. **Java:** The primary programming language used for the Android application.
5. **Authentication:** **Firebase Authentication** is used for user identity verification.
6. **XML:** Used for designing the Android user interface (UI).
7. **Android SDK:** Utilized for development tools and API libraries.
8. **Machine Learning:** A model was developed to generate a personality analysis based on users' scoring (1-5) of 50 questions. This analysis is displayed on user profiles.
9. **API:** A custom API was written to access the developed machine learning model. The app receives responses from the model using this API.
   > *Note: The API was shut down for security reasons after the project development was completed; therefore, you will not be able to access the ML response when using the app currently.*

## Demo Video
https://github.com/SemihGul5/KonumUygulamasi/assets/133046330/fefccd4b-f8ff-4f6a-898e-c5d36da4593d
