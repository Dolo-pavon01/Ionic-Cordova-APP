# Ionic Cordova APP

## Description
This is a mobile application developed using the Ionic framework and Cordova. The app is integrated with Firebase for backend services, including Google Analytics 4 (GA4) is used to track and analyze user interactions.

## Features

- **Analytics**: GA4 integration to monitor user events, such as navigation, interactions, and conversions.

## Installation
To install and run the app locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/Ionic-Cordova-APP.git
   cd Ionic-Cordova-APP

2. **Install dependencies:**

    ```bash
    npm install

3. **Firebase Setup:**

- Create a project in the Firebase Console.
- Set up Authentication, Firestore, and Storage.
- Download the google-services.json file and place it in the src/ directory.
- Run the app in the browser (development mode):

   ```bash
  ionic serve

4. **Build the app for production:**

     ```bash
    ionic build

5. **Run the app on an emulator or device:**

For Android:

     ```bash
    ionic cordova run android
    
For iOS:

     ```bash
    ionic cordova run ios
    
## Google Analytics 4 Usage
We have set up GA4 to track events such as:

- User logins
- New user registrations
- Interactions and preferences
- Screen navigation
  
This data helps us better understand user behavior and improve the app's user experience.
