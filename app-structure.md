# Mobile App File Structures for Popular Frameworks

This document outlines typical project file structures for mobile apps developed in **Android Studio** (Native Android), **React Native**, **Flutter**, and **Xcode** (Native iOS). Each section lists common files and folders created by default for a new project.

---

## 1. Android Studio (Native Android - Java/Kotlin)

```
MyApp/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── example/
│   │   │   │           └── myapp/
│   │   │   │               ├── MainActivity.java
│   │   │   │               └── ...
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml
│   │   │   │   ├── drawable/
│   │   │   │   ├── mipmap/
│   │   │   │   ├── values/
│   │   │   │   │   └── strings.xml
│   │   │   │   │   └── colors.xml
│   │   │   │   │   └── styles.xml
│   │   │   ├── AndroidManifest.xml
│   ├── build.gradle
├── build.gradle
├── settings.gradle
├── gradle/
│   └── wrapper/
├── gradlew
├── gradlew.bat
└── local.properties
```

---

## 2. React Native

```
MyApp/
├── android/
│   └── ... (Android native files)
├── ios/
│   └── ... (iOS native files)
├── src/
│   ├── components/
│   ├── screens/
│   ├── App.js
│   └── ...
├── package.json
├── index.js
├── babel.config.js
├── metro.config.js
├── .gitignore
├── node_modules/
├── app.json
└── README.md
```

---

## 3. Flutter

```
my_app/
├── android/
│   └── ... (Android native files)
├── ios/
│   └── ... (iOS native files)
├── lib/
│   ├── main.dart
│   ├── screens/
│   └── widgets/
├── test/
│   └── widget_test.dart
├── pubspec.yaml
├── pubspec.lock
├── .gitignore
├── README.md
├── build/
├── web/
│   └── index.html
├── macos/
├── windows/
├── linux/
└── assets/
    ├── images/
    └── fonts/
```

---

## 4. Xcode (Native iOS - Swift/Objective-C)

```
MyApp/
├── MyApp.xcodeproj
├── MyApp.xcworkspace
├── MyApp/
│   ├── AppDelegate.swift
│   ├── SceneDelegate.swift
│   ├── ViewController.swift
│   ├── Assets.xcassets/
│   ├── Base.lproj/
│   │   └── LaunchScreen.storyboard
│   │   └── Main.storyboard
│   └── Info.plist
├── Pods/
├── Podfile
├── Podfile.lock
├── .gitignore
└── README.md
```

---

**Notes:**
- The above structures represent standard boilerplate layouts and may expand depending on project scale and external dependencies.
- For cross-platform frameworks (React Native, Flutter), Android and iOS folders contain native code for respective platforms.
- Asset directories and configuration files (.gitignore, README, etc.) are included for best practices.
