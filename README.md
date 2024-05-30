# Pomofocus App

Pomofocus is a productivity app designed to help users manage their time effectively using the Pomodoro Technique. The Pomodoro Technique is a time management method developed by Francesco Cirillo in the late 1980s. It's based on the idea of breaking work into focused intervals, typically 25 minutes in length, separated by short breaks. This technique aims to improve productivity and concentration by providing structured work periods and regular breaks.

This mobile app for Android is inspired by the Pomofocus web application, offering similar functionality for convenient time management and productivity enhancement on mobile devices.

## About the Pomodoro Technique

The Pomodoro Technique consists of six basic steps:

1. **Choose a Task**: Select a task you want to work on.
2. **Set the Pomodoro**: Set a timer (traditionally to 25 minutes) for your work session.
3. **Work on the Task**: Focus on the task until the timer rings.
4. **Take a Short Break**: Take a short break (typically 5 minutes) to rest and recharge.
5. **Repeat**: After completing a work session and break, repeat the process.
6. **Longer Breaks**: After completing a set number of work sessions (usually four), take a longer break (typically 15-30 minutes).

## DEMO
Watch a video demonstration of the application and turn on the sound for a better experience.

https://github.com/saparbekuly/Pomofocus/assets/164681008/9604ca9c-b7aa-4f51-896d-f82ccc870bbb

## Features

- **Pomodoro Timer**: Default 25-minute work sessions with adjustable time settings.
- **Break Timer**: Default 5-minute break sessions with adjustable time settings.
- **Notifications**: Alerts when a session is complete.
- **Sound Alerts**: Plays an alarm sound when a session ends.
- **Custom Time Picker**: Allows users to set custom durations for work and break sessions.
- **Navigation**: Switch between Pomodoro and Break screens.
- **Dark Theme Support:**: Pomofocus seamlessly adapts to dark mode, ensuring a pleasant experience for users who prefer darker interfaces.


## Setup and Installation

### Prerequisites

- Android Studio
- Android device or emulator running Android 5.0 (Lollipop) or higher

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/saparbekuly/pomofocus.git
    ```

2. Open the project in Android Studio.

3. Build and run the project on your device or emulator.

## Usage

1. **Pomodoro Timer**:
    - Press `START` to begin the 25-minute work session.
    - Press `PAUSE` to pause the timer.
    - Click on the timer to set a custom duration.

2. **Break Timer**:
    - Press `START` to begin the 5-minute break session.
    - Press `PAUSE` to pause the timer.
    - Click on the timer to set a custom duration.

3. **Notifications**:
    - Ensure the app has the necessary permissions to send notifications.
    - Notifications will alert you when a session is complete.

## Code Structure

### MainActivity.kt

- Initializes the app and sets up the navigation between the Pomodoro and Break screens.
- Creates the notification channel.

### Composables

- **PomodoroScreen**: UI and logic for the Pomodoro timer.
- **BreakScreen**: UI and logic for the break timer.
- **TimerButton**: Custom button used in both Pomodoro and Break screens.
- **TimePicker**: Custom time picker dialog.
- **TimerClock**: Circular progress bar showing the remaining time.

### Notifications

- **createNotificationChannel**: Sets up the notification channel for the app.
- **showNotification**: Displays a notification when a session is complete.

### Dependencies

- AndroidX
- Jetpack Compose
- MediaPlayer for sound alerts

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Conclusion

Pomofocus is designed to help you stay productive by using the Pomodoro Technique, encouraging focused work sessions followed by short breaks. We hope you find this app useful in managing your time and enhancing your productivity.

Thank you for using Pomofocus! I am continuously working to improve the app and appreciate any feedback or contributions. Feel free to reach out if you have any suggestions or encounter any issues.

For any queries or issues, please contact [beibit.saparbekuly@gmail.com].

Happy focusing!
