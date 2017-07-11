# OneMobileSDK-releases-android
Location for Andorid Maven Artifacts for OneMobileSDK.

1. add a reference to our maven repo:

allprojects {
    repositories {
        maven { url 'https://raw.github.com/aol-public/OneMobileSDK-releases-android/maven/'}
    }
}

2. and update your dependency to our SDK binary:

dependencies {
    compile 'com.aol.one.publishers.android:sdk:2.11'    // for example
}
