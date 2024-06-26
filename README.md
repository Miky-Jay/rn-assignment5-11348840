# rn-assignment5-11348840

## Mobile Application Development Assignment 5

This project is a React Native mobile application developed using Expo. The app includes a bottom tab navigator with Home and Settings screens and allows users to switch between light and dark themes.

### Features

- Bottom Tab Navigator
- Home and Settings Screens
- Light and Dark Theme Switching

### Installation

1. **Clone the repository**:

   ```sh
   git clone https://github.com/your-username/rn-assignment5-11348840.git
   cd rn-assignment5-11348840
   ```

2. **Install dependencies**:

   ```sh
   npm install
   ```

3. **Run the project**:
   ```sh
   npm start
   ```

### Navigation Setup

Installed the necessary navigation packages:

```sh
npm install @react-navigation/native @react-navigation/bottom-tabs @react-navigation/native-stack react-native-screens react-native-safe-area-context react-native-gesture-handler react-native-reanimated react-native-redash
```

```

### Screenshots

![Home Screen](screenshots/home-screen.png)
![Settings Screen](screenshots/settings-screen.png)

### Custom Components

- **BottomTabNavigator.js**: Defines the bottom tab navigation structure.
- **HomeScreen.js**: The Home screen component.
- **SettingsScreen.js**: The Settings screen component.

### Theme Switching

The app uses React Native Paper's `Provider` component to switch between light and dark themes.
```
