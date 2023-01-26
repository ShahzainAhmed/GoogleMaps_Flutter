# Google Maps Integration in Flutter
- Add the Google Maps Flutter package to your project from https://pub.dev/packages/google_maps_flutter
- Set the minSdkVersion in android/app/build.gradle to 20 like: 
```
android {
    defaultConfig {
        minSdkVersion 20
    }
}
```
- Specify your API key in the application manifest android/app/src/main/AndroidManifest.xml
```
<manifest ...
  <application ...
    <meta-data android:name="com.google.android.geo.API_KEY"
               android:value="YOUR KEY HERE"/>
```
</br>
<p align="center" width="100%">
    <img width="33%" src="https://user-images.githubusercontent.com/59369881/214812762-7d53a561-e281-4af8-8d4d-46ffa73b00d2.png">
</p>
