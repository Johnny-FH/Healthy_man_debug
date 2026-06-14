The app won't work immediately after downloading. It's been cleared of connections to Firebase and Google.

1. Create a Firebase project.
2. Connect the app to the Firebase project.
3. Add the SHA-1 key from Android Studio to the Firebase project.
4. Create a Realtime Database.
5. Enable Google Authentication in Firebase.
6. Download the Google Service file and upload it to Android Studio.
7. Replace:
"default_web_client_id xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx" in strings. xml with your client ID from Google Authentication.

The app will start working at this point. Ads will work in testmod unless you create your own project in Google AdMob and replace test id's:
"banner_ad_unit_id ca-app-pub-3940256099942544/9214589741" and 
"APPLICATION_ID" android:value="ca-app-pub-3940256099942544~3347511713" in the Android Manifest file.
