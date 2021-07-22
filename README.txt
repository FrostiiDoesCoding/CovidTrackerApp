NOTES:
-Settings = Notifications, Search = Dashboard, Home = home.
-The local location feature 100% works on Android 29. However it doesn't fully work on Android 24 emulators based on testing(since it's a geocoder), 
and sometimes the app won't get location properly and get the default "Fairfax, VA" instead. It works on one of our emulators, but not another one's.
(We didn't realize that it didn't work on 24 until a couple of days ago and we didn't have time to reimplement to make this feature compatible with 24) 
-Because of this, for Android 29, it will initially show the default location (So on a fresh install, because it asks for permissions first). 
Switching tabs to and back or relaunching after giving permissions should correct it and give the location.
-Don't switch between the tabs too fast. It will crash the app.
-ALL SCREENS ARE SCROLLABLE AS WELL.