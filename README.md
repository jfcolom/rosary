# Rosary
Help for praying the christian Holy Rosary

## Current functionality

This is a very simple app helping christian users to pray the [Rosary](https://en.wikipedia.org/wiki/Rosary).
It basically shows biblical texts for the mysteries in an ordered way, and simulate beads to count _Hail Mary_ prayers.
Currently, it supports English and Spanish language. The texts come from [vatican.va](http://www.vatican.va/special/rosary/index_rosary.htm).

[<img src="https://f-droid.org/badge/get-it-on.png"
     alt="Get it on F-Droid"
     height="90">](https://f-droid.org/packages/org.example.rosary/)

## Development

This is just an HTML page with a background and some CSS layers and Javascript.
The [Cordova](https://cordova.apache.org/) framework has been used in order to generate an Android project that can be built to produce an APK from the HTML page.
The required files generated by Cordova have been uploaded, so building the app does not require Cordova installation.

## Build

Application can be built using [gradle](http://www.gradle.org).

To generate the apk :

	gradle build
