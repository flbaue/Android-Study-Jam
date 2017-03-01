# Android-Study-Jam
All the material for the Android Study Jam at Women Techmakers Hamburg

Everything here is **work in progress** and **up to discussion**!

## Goal of the course
The goal is to give interested people that might not a programming background, but could have, an introduction to how an android app is build and how things can be achived. This course is not meant to provide some kind of professional training that enables people to become productive developers. People of all skill levels should have some kind of success experience. Therfore there should be simple tasks to start with and more advanced tasks towards the end.

## WTM-Messenger
This is the reference app that we want to build during the course. The idea is a simple WhatsApp like chat application that uses Firebase as its backend.

In the end there should be branches here, that contain each feature step by itself. That way someone could just checkout a specific branch and compare to their own implementation or continue from there.

### Proposed feature steps
Not all must be accomplished

1. Send and receive text messages and display them in a list (Recycler View).

2. Make users identifiable by a name

3. Send and receive images

4. Users can create chat groups with individuals or groups

5. Provide login functionality

### Good-to-have-but-not-needed previous knowledge (especially this is open for discussion :-) )

* Java

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
  
  
### Questions to either talk about or address in the guides
* How does the Firebase Realtime Database work?
* What are JSON and XML? Which role do they play in our daily lifes?
* How does an Android app work (`Activities`, `Fragments`, `Views`, `Activity#setContentView`, `Context`)?
* What is the Design / Support Library?
* (What is a library?)
* What is Gradle?
