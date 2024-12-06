# Flutter Advanced Navigation

This Flutter application demonstrates advanced navigation techniques, such as using a `Drawer` for navigation, implementing a `BottomNavigationBar` for page switching, and navigating between multiple screens using named routes. It provides a clean and user-friendly structure to better understand Flutter's routing and navigation system.

## Features:
- **Main Screen**: The main screen includes a navigation menu with a `Drawer` and a `BottomNavigationBar` that allows the user to switch between different screens.
- **First Screen**: A simple screen with a button that navigates to the second screen.
- **Second Screen**: A screen with a button that navigates to the third screen.
- **Third Screen**: A screen with a button that navigates back to the first screen.

## Approach:

In this project, I have employed the following advanced navigation techniques:

### 1. **Drawer Navigation**:
   The `Drawer` widget is used for vertical navigation, providing a side menu that can be accessed by swiping or clicking a hamburger icon. This is a common pattern used in mobile apps to enable easy access to different sections of the application.

### 2. **Bottom Navigation Bar**:
   The `BottomNavigationBar` widget allows users to easily switch between different sections of the application. Each tab in the bottom navigation corresponds to a different screen, making it convenient for users to move between views.

### 3. **Named Routes**:
   Named routes in Flutter allow you to map a string identifier to a specific screen. This is particularly useful in larger applications for better navigation management and for keeping track of screen transitions. Instead of managing navigation logic with `Navigator.push()`, we use `Navigator.pushNamed()`.

## Challenges Faced:
- **Handling State with BottomNavigationBar**: Managing the state across the screens to ensure the active tab and screen are properly synchronized was a bit tricky. I used the `IndexedStack` widget to preserve the state of each screen while switching tabs.
- **Managing Navigation Logic**: Ensuring that the app's navigation works smoothly with both `Drawer` and `BottomNavigationBar` involved careful management of the `Navigator` stack, especially when combining named routes with direct navigation.
- **Customizing the Drawer**: Customizing the `Drawer` widget to make it look appealing and functional required some experimentation, especially to make it interact seamlessly with the bottom navigation.

---

## How to Run the Application:

Follow these steps to run the Flutter application:

### 1. Install Flutter:
   Ensure you have Flutter installed. If you haven’t already done so, follow the [official Flutter installation guide](https://flutter.dev/docs/get-started/install) to set up Flutter on your machine.

### 2. Clone the Repository:
   Clone the repository to your local machine using Git:
   ```bash
   git clone https://github.com/yourusername/flutter-advanced-navigation.git
```

### 3. open vscode:
   open vscode and open the file that you clone

### 4. unduh depedency:
 type ``` flutter pub get ``` to download depedency

### 5. check device:
type ```flutter devices``` to check your devices flutter

### 6. run flutter:
   if all is done then type ``` flutter run ```
