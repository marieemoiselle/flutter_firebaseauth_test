# Flutter 🫱🏼‍🫲🏽 Firebase Test App

Hello! 🙋🏻‍♀️<br/>
This is an example Flutter project that you can use in integrating Firebase Authentication.

## 🐣 Instructions
Integrate the Firebase Google Authentication in this Flutter project. In the ```LoginScreen``` the user must be able to sign in to Google after tapping the ```ElevatedButton```. Once sign in is successful, the user will be redirected to the ```WelcomeScreen``` that contains a ```Drawer``` with a ```Log out``` option. Once it is tapped, the user will be sent back to the ```LoginScreen```. Feel free to customize the colors, themes, and the overall feel of the application, after you successfully complied with the requirement.

## 🤔 What to prepare
**Install Node.js**<br/>
Node.js and npm (Node Package Manager) are required to be installed on your system. [Install Node.js](nodejs.org)

**Install Firebase CLI**<br/>
After installing Node.js, open the command prompt and install the Firebase CLI globally using npm.
```
npm install -g firebase-tools
```

**Verify Installation**<br/>
Run the following command to show the version of the installed Firebase CLI:
```
firebase --version
```

**Install Flutter/Dart** <br/>
Follow these instructions on how to properly install Flutter on your device. <br/>
[How To Install Flutter For Windows - Build Flutter Apps 1 | Codemy.com | YouTube](https://www.youtube.com/watch?v=VFDbZk2xhO4)

**Using Firebase CLI with Flutter**<br/>
After installing the Firebase CLI, initialize it in your project using the command:
```
firebase init
```

## 🔗 Integrating Firebase Auth to your Flutter Project
**Create a Firebase Project.** Go to the [Firebase Console](https://console.firebase.google.com) and create a new project.

**Add Firebase to your Flutter app.** Follow the instructions in Firebase for adding it to your Flutter project.

**Flutter Packages.** Ensure that these Flutter packages are installed:
```
flutter pub add firebase_core
flutter pub add firebase_auth
```

**Configuring Firebase Authentication.** To enable Google Sign-in button in Firebase Console, go to your Firebase project, navigate to ***Authentication > Sign-in method***, and then enable Google as a sign in provider.

**Flutter Code Implementation.** A Flutter project with a login screen and welcome screen are already provided in this repository. Apply the sign in code in the ```ElevatedButton```'s function.

**Handling Authentication State.** Create checks if the user is signed in. If sign-in is successful, the ```WelcomeScreen``` appears.

**Follow this guide**<br/>
To know more, you can watch this guide to implement the Google Sign In in Flutter via Firebase:
[How To Implement Google Sign-In Functionality In Flutter With Firebase and FlutterfireCLI](https://www.youtube.com/watch?v=JEqlf0uBRyE).
<br/>Thank you so much, [CodeWithDarkwa](https://www.youtube.com/@CodeWithDarkwa), it really helped!

## 🔄️ Clone this Repository
To create your copy of this repository, input the following command:
```
git clone https://github.com/<username/repository-name>.git
```
Change the values inside the ```<``` and ```>```.
## 🫶🏻 Acknowledgments
👍🏻 [CodeWithDarkwa - YouTube](https://www.youtube.com/@CodeWithDarkwa)<br/>
👍🏻 [Codemy.com - YouTube](https://www.youtube.com/@Codemycom)<br/>
🏫 IT 331 - Application Development and Emerging Technologies Course Facilitators<br/>
🩶 My cutie best friend, Gerald James Da&ntilde;o<br/>
🩵 Jerome Fabregar
