# OneMobileSDK-releases-android
Location for Andorid Maven Artifacts for OneMobileSDK.

## Build integration guide 

### Add a reference to our maven repo:

```gradle
allprojects {
    repositories {
        maven { url 'https://raw.github.com/aol-public/OneMobileSDK-releases-android/maven/' }
    }
}
```

### Update your dependency to our SDK binary:

```gradle
dependencies {
    compile 'com.aol.one.publishers.android:sdk:2.12'    // Use specific version
}
```
