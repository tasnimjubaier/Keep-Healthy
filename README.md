# Keep Healthy

An Android application designed to help users maintain a healthy lifestyle through fitness tracking, health monitoring, and wellness management.

## 📱 Overview

Keep Healthy is a native Android application built with Java that aims to empower users to take control of their health and wellness journey. The app provides tools and features to track various health metrics and maintain healthy habits.

## ✨ Features

- **Health Tracking**: Monitor various health metrics and wellness indicators
- **User-Friendly Interface**: Intuitive and clean design for easy navigation
- **Native Android Experience**: Built with Java for optimal Android performance
- **Offline Capability**: Access core features without internet connection
- **Lightweight**: Optimized for minimal battery and storage usage

## 🛠️ Technology Stack

- **Language**: Java
- **Platform**: Android
- **Build System**: Gradle
- **IDE**: Android Studio
- **Min SDK**: Android 5.0 (API level 21) or higher

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Android Studio** (latest version recommended)
- **Java Development Kit (JDK)** 8 or higher
- **Android SDK** with appropriate API levels
- **Gradle** (usually bundled with Android Studio)
- An Android device or emulator for testing

## 🚀 Getting Started

### Installation Steps

1. **Clone the repository**:
```bash
git clone https://github.com/tasnimjubaier/Keep-Healthy.git
cd Keep-Healthy
```

2. **Open in Android Studio**:
   - Launch Android Studio
   - Select "Open an Existing Project"
   - Navigate to the cloned directory
   - Click "OK" and wait for Gradle sync to complete

3. **Build the project**:
   - Click on "Build" → "Make Project" or use `Ctrl+F9` (Windows/Linux) / `Cmd+F9` (Mac)
   - Wait for the build to complete successfully

4. **Run the application**:
   - Connect an Android device via USB with USB debugging enabled, OR
   - Set up an Android emulator through AVD Manager
   - Click "Run" → "Run 'app'" or press `Shift+F10`

### Using Gradle from Command Line

#### Build the project:
```bash
./gradlew build
```

#### Install on connected device:
```bash
./gradlew installDebug
```

#### Run tests:
```bash
./gradlew test
```

#### Create release APK:
```bash
./gradlew assembleRelease
```

## 📁 Project Structure

```
Keep-Healthy/
├── .idea/                  # Android Studio configuration files
├── app/                    # Main application module
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/      # Java source files
│   │   │   ├── res/       # Resources (layouts, drawables, values)
│   │   │   └── AndroidManifest.xml
│   │   ├── androidTest/   # Instrumented tests
│   │   └── test/          # Unit tests
│   └── build.gradle       # App-level build configuration
├── gradle/
│   └── wrapper/           # Gradle wrapper files
├── build.gradle           # Project-level build configuration
├── gradle.properties      # Gradle properties
├── gradlew                # Gradle wrapper script (Unix)
├── gradlew.bat            # Gradle wrapper script (Windows)
├── settings.gradle        # Gradle settings
├── .gitignore            # Git ignore rules
└── README.md             # Project documentation
```

## 🎯 Key Components

### Activities
Main screens and user interface components of the application.

### Fragments
Reusable UI components for modular design.

### Services
Background operations and data processing.

### Adapters
Data binding for list views and recycler views.

### Models
Data structures and business logic.

## 🔧 Configuration

### Gradle Configuration

The project uses Gradle as its build system. Key configuration files:

- **build.gradle (Project)**: Project-level dependencies and repositories
- **build.gradle (App)**: App-level dependencies, SDK versions, and build types
- **gradle.properties**: Gradle-specific properties and JVM arguments
- **settings.gradle**: Project settings and module inclusion

### Android Manifest

The `AndroidManifest.xml` file contains:
- App permissions
- Activity declarations
- App metadata and configuration

## 🧪 Testing

### Running Unit Tests
```bash
./gradlew test
```

### Running Instrumented Tests
```bash
./gradlew connectedAndroidTest
```

### Test Coverage
Generate test coverage reports:
```bash
./gradlew jacocoTestReport
```


## 📞 Contact

For questions, suggestions, or feedback:
- Open an issue on [GitHub](https://github.com/tasnimjubaier/Keep-Healthy/issues)


---

**Stay Healthy, Stay Happy!** 💪🏃‍♂️🥗
