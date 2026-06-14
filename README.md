The app won't work immediately after downloading. It's been cleared of connections to Firebase and Google.

1. Create a Firebase project.
2. Connect the app to the Firebase project.
3. Add the SHA-1 key from Android Studio to the Firebase project.
4. Create a Realtime Database.
5. Enable Google Authentication in Firebase.
6. Download the Google Service file and upload it to Android Studio.
7. Replace:
<string name="default_web_client_id" >xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx</string> to your client ID from Google Authentication.

The app will start working at this point. Only the ads won't work unless you create your own project in Google AdMob and replace:
<string name="banner_ad_unit_id">xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx</string> and 
<meta-data android:name="com.google.android.gms.ads.APPLICATION_ID" android:value="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"/>
