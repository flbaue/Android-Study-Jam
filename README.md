# Android-Study-Jam
All the material for the Android Study Jam at Women Techmakers Hamburg

Everything here is work in progress and up to discussion!

## WTM-Messenger
This is the reference app that we want to build during the course. The idea is a simple WhatsApp like chat application that uses Firebase as its backend.

### Proposed feature steps
Not all must be accomplished

1. Send and receive text messages and display them in a list (Recycler View).

2. Make users identifiable by a name (Firebase Authentication)

3. Send and receive images

4. Users can create chat groups with individuals or groups

5. Provide login functionality

### Prerequisites
* The latest version of Android Studio, including the latest support library revision
* (Github account)?
* A Google account
* Android 7.1.1 (API 25) (this is the latest as of 28/02/2017, it may change over time) SDK Platform and Google Play Services from the SDK Manager

### First steps
0. Download the boilerplate code from github.com/flbaue/Android-Study-Jam and open it in Android Studio
1. Firebase setup
  1. Go to console.firebase.google.com and log in with your Google Account
  2. Create a new project
    1. Select a name and choose Germany for country
  3. Take a look around and get familiar with the Firebase Console / Dashboard
  4. Go to 'Overview' and select 'Add Firebase to your Android app'
    1. Enter the package name ("de.moinworld.wtm_messenger") which you can find in the module-wide build.gradle
    2. Enter the name of the app (something along the lines of "WTM Messenger")
    3. Click add and follow the steps (Add google-services.json to your project and add the Gradle dependencies
  4. Alternatively, in Android Studio, click Tools -> Firebase -> Realtime Database -> Save and retrieve data -> Connect to Firebase -> Add the Realtime Database to your app
  5. That's it, Firebase is set up and ready to go :-)
  
