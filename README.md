# google-dev-products

Arsa Daris Gintara
13519037

ANDROID STUDIO

Android Studio is the official Integrated Development Environment (IDE) for Android app development, one of products that google provide.
App in Android Studio can be written in Java, Kotlin, and C++ languanges that will be compiled into an .apk file that contains
all the contents of an Android app and it is the file to install the app.

To get to know how an Android app is written, i followed the tutorial in https://developer.android.com to build a simple "Hello World" program.
can be found here https://github.com/arsa-dg/first-androidstudio

Apps provide multiple entry points, it means that android apps are built as a combination of components that can be invoked individually.
"activity" is a type of component that provides a user interfece, and "main" activity is the ui that will show when an app icon is tapped.
But, to direct to an activity can be from anywhere, such "main" activity can be directed from a notification or even a different app.

Apps adapt to different devices, it means android allows us to provide different resources for different devices such as different layout,
settings based on the condition of the current device (screen size or anything).

Every project have these files.
1. under app>java>(package-name)>MainActivity
this is the main activity, the entry point of the app. When we build and run this app, the system launches an instance of this activity and
loads its layout

2. under app>res>layout>activity_main.xml
this xml file defines the layout for the activity's UI.

3. under app>manifests>AndroidManifest.xml
describes the fundamental characteristic of the app and defines each of its components

4. under Gradle Scripts>build.gradle
one for project "Project: (nameproject)", and one for app module "Module: app"
