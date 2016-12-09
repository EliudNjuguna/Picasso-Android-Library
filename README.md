# Picasso-Android-Library

Picasso Android Library offers an easy way to download and caching images in your android app. 
Picasso Android Library is open source and widely used by android developers as their favorite image downloader in apps

How to use Picasso in android studio?
Adding Picasso library for android studio is really simple, just add one dependency

Now open your project’s build.gradle from the project’s home directory and add the following dependency.
build.gradle
1
compile 'com.squareup.picasso:picasso:2.5.2'
Since we need to connect to the Network add the Internet permission in AndroidManifest.xml file.
1
<uses-permission android:name="android.permission.INTERNET"/>
