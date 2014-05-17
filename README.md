With 3.4, here is what works for me:

Create your project

cordova create example com.example Example
Change to your project directory and then add Android

cd example
cordova platform add android
Get the plugin

cordova plugin add https://github.com/wildabeast/BarcodeScanner.git
Build the project

cordova build android
After that everything appeared to be in the right place.