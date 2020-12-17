

How to Add your own firebase platform to this app

https://firebase.google.com/docs/android/setup
Firebase guides you through this as you make a new project, but i've done most of this so all you need to do is.

Step 1: Create firebase project

Step 2: Find your app's package name in your module (app-level) Gradle file,
        usually app/build.gradle (example package name: com.yourcompany.yourproject)

Step 3: Download the google-services.json file firebase gives you and replace the file in this repository
        android/app/google-services.json

Step 4: Enable Email/Password authentication in the authentication tab.

Step 5: Create a cloud firestore project (Updated version of real time database)

Step 6: In the fire store Rules set "allow read , write" to "True" **Important for chat**
        http://prntscr.com/w4o34c image example.
