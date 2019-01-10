**Limited Support Notice**
--------------------------
This plugin, bindings, and sample code are meant for example purposes only.  This example will no longer run out of the box from this Github project.  This project is intended to be reference code for how you can integrate ZoOm as a native plugin in the Cordova/Ionic/PhoneGap ecosystem.  This example was based on an earlier version of ZoOm (6.5.0), which we no longer support and will not function if you attempt to use it.

If you are familiar with Cordova/Ionic/PhoneGap and Native Modules in these ecosystems, this plugin and the sample provided is 90% of the work to get ZoOm working in your Cordova/Ionic/PhoneGap app.  The remaining work is in updating the bindings to our latest released Native iOS and Android libraries (7.0.0)+, which can be downloaded here - https://dev.zoomlogin.com/zoomsdk/#/downloads.

Hopefully this is enough to get you going!

If you have any more technical questions please feel free to contact us at support@zoomlogin.com
------------------------------
**End Limited Support Notice**

ZoOm SDK Cordova Example
------------------------
This application provides a simple example for using the ZoOm SDK Cordova plugin.  

Preparing the Sample App
------------------------
Before the app can be built correctly, all platforms must be added by running `cordova platform add android` and `cordova platform add ios` from the command line while in the project directory.

Installing the Plugin
---------------------
After cloning this project, the ZoOm plugin must first be installed by running `cordova plugin add https://github.com/facetec/cordova-plugin-zoom-sdk` from the command line.  For more details about the plugin, [see here](https://github.com/facetec/cordova-plugin-zoom-sdk).

Setting Your App Token
----------------------
In index.js, modify the following line to contain your ZoOm app token:
```javascript
var appToken = "SET YOUR TOKEN HERE";
```
If you do not have an app token, register for [developer access](https://dev.zoomlogin.com/).

Running the Application
-----------------------
Run `cordova run android` or `cordova run ios` to build and install the app.  For more complete instructions, see the [Cordova](https://cordova.apache.org/#getstarted) documentation. 
