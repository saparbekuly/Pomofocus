# Pomofocus App

Pomofocus is a productivity app based on the Pomodoro Technique. It helps users work with time rather than against it by breaking work into intervals, traditionally 25 minutes in length, separated by short breaks.

## Features

- **Pomodoro Timer**: Default 25-minute work sessions with adjustable time settings.
- **Break Timer**: Default 5-minute break sessions with adjustable time settings.
- **Notifications**: Alerts when a session is complete.
- **Sound Alerts**: Plays an alarm sound when a session ends.
- **Custom Time Picker**: Allows users to set custom durations for work and break sessions.
- **Navigation**: Switch between Pomodoro and Break screens.

## Screens

- **Pomodoro Screen**: Displays the Pomodoro timer and navigation to the Break screen.
- **Break Screen**: Displays the Break timer and navigation to the Pomodoro screen.

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

## Dependencies

- AndroidX
- Jetpack Compose
- MediaPlayer for sound alerts

## Permissions

- **POST_NOTIFICATIONS**: To show notifications when a session is complete.

## Customization

- You can customize the duration of the Pomodoro and break sessions.
- Modify the notification messages and sounds as per your preference.

## Contributing

Feel free to fork the repository and make changes. Pull requests are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [Jetpack Compose](https://developer.android.com/jetpack/compose) for the UI components.
- Icons and images used in the app.

## Contact

For any queries or issues, please contact [beibit.saparbekuly@gmail.com].

## Conclusion

Pomofocus is designed to help you stay productive by using the Pomodoro Technique, encouraging focused work sessions followed by short breaks. We hope you find this app useful in managing your time and enhancing your productivity.

Thank you for using Pomofocus! We are continuously working to improve the app and appreciate any feedback or contributions. Feel free to reach out if you have any suggestions or encounter any issues.

Happy focusing!
