# BWStory - React Native Developer Assignment

BWStory is a React Native mobile application developed as part of the **Blackcoffer React Native Developer Test Assignment**.

The project recreates and enhances the **Discover** and **Profile** screens of the BWStory application with a modern dark-themed interface, reusable components, responsive layouts, and interactive UI elements.

---

## 📱 Screens Implemented

### Discover Screen

The Discover screen provides a content discovery experience with:

- Stories section
- Horizontal category filters
- Featured/trending story cards
- Compact news/story cards
- Search functionality
- Category-based filtering
- Like interactions
- Bookmark interactions
- Author information
- Engagement statistics
- Responsive scrolling interface
- Custom dependency-free icons

### Profile Screen

The Profile screen includes:

- Profile cover image
- User avatar and verification badge
- User biography
- Interest tags
- Posts, followers, and following statistics
- Follow / Following interaction
- Message button UI
- Share button UI
- Posts tab
- Saved stories tab
- About tab
- Recent posts image grid
- Saved story cards
- Profile information section
- Animated cover/header behavior

---

## ✨ Features

- Modern dark UI
- Responsive React Native layouts
- Bottom tab navigation
- Discover and Profile screens
- Interactive search
- Category filtering
- Like and bookmark states
- Follow / Following state
- Profile content tabs
- Animated scrolling effects
- Reusable design system
- Centralized colors, spacing, typography, radius and shadows
- Mock data architecture for easy backend integration
- Android support

---

## 🛠 Tech Stack

- React Native
- React
- JavaScript / TypeScript
- React Navigation
- React Native Animated API
- Android SDK
- Gradle
- npm

---

## 📂 Project Structure

```text
BWStoryNative/
│
├── android/
├── ios/
├── src/
│   ├── assets/
│   ├── components/
│   ├── data/
│   │   └── mockData.js
│   ├── navigation/
│   │   └── AppNavigator.js
│   ├── screens/
│   │   ├── DiscoverScreen.js
│   │   └── ProfileScreen.js
│   └── theme.js
│
├── App.tsx
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Before running the project, make sure the following are installed:

- Node.js
- npm
- JDK 17
- Android Studio
- Android SDK
- Android Emulator or physical Android device

---

## 1. Install Dependencies

Open a terminal in the project root:

```bash
npm install
```

---

## 2. Start Metro

Run:

```bash
npm start
```

Or:

```bash
npx react-native start
```

Keep the Metro terminal running.

---

## 3. Run on Android

Open another terminal in the project root and run:

```bash
npm run android
```

Or:

```bash
npx react-native run-android
```

Make sure an Android emulator is running or an Android device is connected.

---

## 🔧 ADB Connection

If Metro is running but the Android application cannot connect to it, run:

```bash
adb reverse tcp:8081 tcp:8081
```

Then reload the application.

---

## 📦 Build Android APK

Navigate to the Android directory:

```bash
cd android
```

### Debug APK

```bash
./gradlew assembleDebug
```

On Windows PowerShell:

```powershell
.\gradlew assembleDebug
```

The generated APK can be found at:

```text
android/app/build/outputs/apk/debug/app-debug.apk
```

### Release APK

```bash
./gradlew assembleRelease
```

On Windows PowerShell:

```powershell
.\gradlew assembleRelease
```

The generated release APK can normally be found at:

```text
android/app/build/outputs/apk/release/app-release.apk
```

---

## 🎨 Design Approach

The application uses a centralized design system through `src/theme.js`.

It contains reusable values for:

- Colors
- Typography
- Spacing
- Border radius
- Shadows
- Icon sizes
- Avatar sizes
- Component dimensions
- Animation timings
- Common styles

This keeps the Discover and Profile screens visually consistent and makes the UI easier to maintain.

---

## 🗃 Data Architecture

The application currently uses mock data stored in:

```text
src/data/mockData.js
```

The UI is separated from the data definitions so that the mock data can later be replaced with API/backend data without requiring major changes to the screen layouts.

---

## 📱 Navigation

The application uses bottom tab navigation.

The main implemented assignment screens are:

- **Discover**
- **Profile**

Additional navigation items are included as UI placeholders to provide a more complete application experience.

---

## 🧪 Testing

The application has been tested on Android using an Android emulator.

Important flows tested include:

- Application startup
- Discover screen scrolling
- Search
- Category selection
- Like interaction
- Bookmark interaction
- Bottom navigation
- Profile screen
- Follow / Following interaction
- Posts tab
- Saved tab
- About tab

---

## 📌 Assignment Scope

This project was created specifically for the React Native developer assignment.

The primary focus of the implementation is the UI and user experience of the **Discover** and **Profile** screens.

The project uses mock content for demonstration purposes and does not require a production backend.

---

## 👨‍💻 Developer

**Rakshit Soni**

React Native / Frontend Developer

---

## 📄 Notes

- Internet access may be required to load remote demonstration images.
- The project is optimized primarily for Android as required for APK submission.
- UI interactions are implemented locally for demonstration purposes.
- Mock data is used instead of a production API.

---

## 📃 License

This project was created for a developer test assignment and demonstration purposes.
