Cordova Testing Project
=======================
Installation
------------
<pre>
npm install -g cordova<pre>
</pre>
<pre>
sudo install gradle
</pre>
Development
-----------
Create New Poject 
<pre>
cordova create myApp
</pre>
Add Platform
<pre>
cordova platform add android
cordova platform add ios
</pre>
Debug Build
<pre>
cordova run android
cordova run ios
</pre>
Release build
<pre>
cordova run android --release -- --keystore=cordova.jks --storePassword=cordova --alias=cordova --password=cordova
</pre>
