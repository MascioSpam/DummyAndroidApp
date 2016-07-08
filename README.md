##Clone the repo

    git clone https://github.com/MascioSpam/DummyAndroidApp.git

##To change the name of the compiled app:
You have to edit:
<ul>
<li>"applicationId"  from "dummy.android.app" to "appid.you.want" in DummyAndroidApp/app/build.gradle</li>
<li>"package" from "dummy.android.app" to "appid.you.want" in DummyAndroidApp/app/src/main/AndroidManifest.xml</li>
<li>"android:label" from "DummyApp" to "TheAppNameYouWantToDisplay" in DummyAndroidApp/app/src/main/AndroidManifest.xml</li>
</ul>

##Build the app:

    cd DummyAndroidApp
    ./gradlew build

##Location of the compiled app-debug.apk:
    DummyAndroidApp/app/build/outputs/apk

##To install through adb
    adb install app/build/outputs/apk/app-debug.apk

###Info
Apk weigh 2.6 KB
Installed app weigh 72 KB
