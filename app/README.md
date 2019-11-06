1. ``keytool -list -v -keystore C:\Users\ggcap\keystore\keystore.jks -alias key0 -storepass nunustudio -keypass nunustudio``
1. ```adb install C:\Users\ggcap\AndroidStudioProjects\mfg\app\build\outputs\apk\release\app-release.apk```
1. ```adb install C:\Users\ggcap\AndroidStudioProjects\mfg\app\build\outputs\apk\debug\app-debug.apk```

[https://stackoverflow.com/questions/57990524/twa-android-app-error-android-support-customtabs-customtabcolorschemeparams-to](https://stackoverflow.com/questions/57990524/twa-android-app-error-android-support-customtabs-customtabcolorschemeparams-to)

1.
````
adb shell "echo '_ --disable-digital-asset-link-verification-for-url=\"https://nns.ngrok.io\"' > /data/local/tmp/chrome-command-line"
````