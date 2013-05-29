JBPM Client
==========

mavenized

This is mavenized version of JBPM Client, Android app for managing JBPM processes and instances in your Android phone.
Target API for this app is 16, because of maven compatibility.

This app was developed as a bachelor work, it's rather a showcase of how to manage JBPM processes on Android than serious Android app for bussines users.

<b>Building guide:</b>

<b>Prerequisities:</b>
JDK 1.6+
Android SDK 16
Maven 3.0.5 (or sooner, then you have to rewrite it in pom.xml)

<b>Set variables:</b>
ANDROID_HOME variable set to your installed Android SDK. Add $ANDROID_HOME/tools and $ANDROID_HOME/platform-tools to $PATH

<b>To run application on emulator:</b>
First, install emulator from Android SDK manager. This app is compatibile with android 3.0+ (API lvl 11).
Before deploying, run emulator. Then run "mvn clean install android:deploy" and "mvn clean install android:run".


