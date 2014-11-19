android-pattern-map
===================

#Overview
Android Pattern - Google Map - How to guide with example.

#Description
This is a quick example on how to get Google maps on your android app running.  One of the few confusing pieces to get right the first time around.  So to save others time I've created this which the docs do not cover and StackOverflow has scattered around.


#Must Have's & stuff you might forget
- Make sure you follow Googles getting started guide: https://developers.google.com/maps/documentation/android/
- Turn on both Google maps v2 AND Google Play Android Developer API.
- Make sure you are using the android studio debug keystore (~./android/debug.keystore) and not your own when adding in the SHA1.  
- Make sure these permissions are inside your manifest:

```
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE"/>
    <uses-permission android:name="android.permission.INTERNET"/>
    <uses-permission android:name="android.permission.ACCESS_WIFI_STATE"/>
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
    <uses-permission android:name="com.google.android.providers.gsf.permission.READ_GSERVICES"/>
```
