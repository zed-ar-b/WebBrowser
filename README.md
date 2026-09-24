# Web Browser for Android 🌐

A lightweight, modern Android web browser application built with **Kotlin** and **Jetpack Compose (Material 3)**.

---

## 🚀 Features

- 🔍 **Smart Address Bar**: Search Google directly or navigate to any URL with automatic `https://` formatting.
- ⚡ **Fast Web Loading**: Full JavaScript, DOM storage, and hardware-accelerated WebView rendering.
- 📊 **Progress Bar**: Visual loading progress indicator integrated smoothly into the top bar.
- ⬅️ **Navigation Controls**: Easy-to-use Back, Forward, and Reload controls.
- 📱 **Hardware Back Button Support**: Handles device back press to navigate web page history before exiting the app using Jetpack Compose `BackHandler`.
- 🎨 **Material 3 Design**: Built using modern Jetpack Compose Material 3 UI components.

---

## 🛠️ Tech Stack & Architecture

- **Language**: [Kotlin](https://kotlinlang.org/) (2.2.x)
- **UI Framework**: [Jetpack Compose](https://developer.android.com/jetpack/compose) with Material 3
- **Web Rendering**: Android `WebView` via `AndroidView` interop
- **Build System**: Gradle Version Catalog (`libs.versions.toml`) with Kotlin DSL (`build.gradle.kts`)
- **Min SDK**: 24 (Android 7.0)
- **Target SDK**: 33 (Android 13) / Compile SDK 37

---

## 📦 Project Structure

```text
WebBrowser/
 ├── app/
 │    └── src/
 │         └── main/
 │              ├── java/com/example/webbrowser/
 │              │    ├── MainActivity.kt        # Main Compose UI and WebView logic
 │              │    └── ui/theme/              # Material 3 Theme, Color, Type definitions
 │              └── AndroidManifest.xml         # Internet permissions & Activity declarations
 ├── gradle/
 │    └── libs.versions.toml                   # Centralized Version Catalog
 ├── build.gradle.kts                           # Root Gradle build script
 └── settings.gradle.kts                         # Repository & plugin management
```

---

## 💻 Getting Started

### Prerequisites
- **Android Studio**: Ladybug / Hedgehog or newer
- **JDK**: Java 17
- **Android SDK**: API 34+

### Building the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/WebBrowser.git
   ```
2. Open the project in **Android Studio**.
3. Let Gradle sync dependencies automatically.
4. Run the app on an Android Emulator or connected physical device (`Shift + F10`).

---

## 🛡️ Permissions

The app requires internet access, declared in `AndroidManifest.xml`:
```xml
<uses-permission android:name="android.permission.INTERNET" />
```

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

<img width="952" height="1921" alt="image" src="https://github.com/user-attachments/assets/eabea19c-4549-4ce5-8731-6a5592479d87" />
Simple Interface:
<img width="1477" height="1783" alt="image" src="https://github.com/user-attachments/assets/94b41d5d-63a6-4c96-93d6-6375dc928457" />
And its working:
<img width="3359" height="2018" alt="image" src="https://github.com/user-attachments/assets/6b811f39-c7c4-4873-8675-da4b0e0488f7" />

