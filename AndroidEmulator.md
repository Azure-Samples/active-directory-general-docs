# Setting up an Android Emulator with Chrome

Thiese instructions are meant to help install Chrome on an Android Emulator.  

If you want to use an emulator out of the box with chrome try one of the following:

- In Visual Studio, use an emulator with Android 25+.
- In Android Studio, use a Pixel or Nexus emulator on Android 21+. 

## Steps 

0. Make sure you're using an emulator with Android 21+. 
1. Install a Chrome APK from a reputable site. For example, [APK Mirror](http://www.apkmirror.com/apk/google-inc/chrome/). Make sure to pick the right apk for your Android version and emulator architecture. 
2. Drag the *.apk file to your emulator, this will automatically install the app.  Go to the app list and Chrome will be listed. 

## More Help

If the above steps aren't working or you encounter some trouble, please open a Github issue or post on StackOverflow.  

Some older versions of Android (4.x), Chrome can have some problems once installed on the device.  If this is the case, we recommend installing Google Play Services and installing Chrome through the app store. For a great write-up of the steps, checkout [this stackoverflow](http://stackoverflow.com/questions/31550628/visual-studio-emulator-for-android-install-gapps-google-play-services?answertab=oldest#tab-top) post. 

    