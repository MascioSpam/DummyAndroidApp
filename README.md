##Clone the repo

    git clone https://github.com/MascioSpam/DummyAndroidApp.git

##To change the name of the compiled app:
You have to edit:
<ul>
<li>"applicationId"  from "dummy.android.app" to "appid.you.want" in app/build.gradle</li>
<li>"package" from "dummy.android.app" to "appid.you.want" in app/src/main/AndroidManifest.xml</li>
<li>"android:label" from "DummyApp" to "TheAppNameYouWantToDisplay" in app/src/main/AndroidManifest.xml</li>
</ul>

##Build the app:

    cd DummyAndroidApp
    ./gradlew build

##Location of the compiled apk:
    cd app/build/outputs/apk
