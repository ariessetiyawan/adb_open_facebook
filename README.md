# adb_open_facebook
How to open Facebook with adb and python

adb shell monkey -p com.facebook.katana -c android.intent.category.LAUNCHER 1
adb shell am start -a android.intent.action.VIEW -d fb://profile
adb shell am start -a android.intent.action.VIEW -d fb://notifications
adb shell am start -a android.intent.action.VIEW -d fb://messages
adb shell am start -a android.intent.action.VIEW -d fb://events

