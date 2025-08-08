![VocalFinder](https://socialify.git.ci/Hazem-Ben-Khalfallah/VocalFinder/image?description=1&descriptionEditable=Android%20app%20to%20find%20your%20phone%20by%20responding%20to%20a%20sound%20you%20have%20emitted%3A%20whistle%2C%20voice%2C%20etc.&forks=1&language=1&logo=https%3A%2F%2Fgithub.com%2FHazem-Ben-Khalfallah%2FVocalFinder%2Fraw%2Fmaster%2Fscreenshots%2Flogo.png&owner=1&pattern=Circuit%20Board&stargazers=1&theme=Light)

# Vocal finder

Did you ever put your phone somewhere and then you forgot where? Did you ever wasted minutes to find it? You should install this app.

This application detects voices and will start vibrating, emitting a ringtone and flash to indicate its position.
Audio sensitivity is configurable to meet our preferences.

## 🚀 Modernization Status

This project has been **fully modernized** for 2024 Android development standards:

### ✅ Updated Build System
- **Gradle**: Updated from 3.3 (2017) to 7.6.4 (2023)
- **Android Gradle Plugin**: Updated from 2.3.1 to 7.4.2
- **Target SDK**: Updated from API 25 (Android 7.1) to API 33 (Android 13)
- **Minimum SDK**: Updated from API 19 (Android 4.4) to API 21 (Android 5.0)

### ✅ AndroidX Migration
- Migrated from Support Library to AndroidX
- Updated all dependencies to modern versions
- ButterKnife updated to 10.x with modern annotations

### ✅ Modern Android Features
- **Notification Channels**: Added for Android 8.0+ compatibility
- **Runtime Permissions**: Enhanced for Android 13+ (including notification permissions)
- **Foreground Services**: Proper implementation with microphone service type
- **Security**: Modern PendingIntent flags and permissions model

### ✅ Compatibility
- **Google Play Store**: Now meets current publishing requirements
- **Modern Devices**: Compatible with Android 5.0 through Android 13+
- **Background Execution**: Handles modern background restrictions
- **Backup Rules**: Added modern backup and data extraction rules

## How does it work?
Start the application. Choose the way in which your lost phone will inform you about its position. You have multiple choices in app settings:
- Ringtone: Choose the sound notification which will be played when the phone is found.
- Configure Ringtone volume when alarm is on.
- flash light: Your phone will start the flash lamp of the camera, which will make finding the phone easier and faster.
- vibration: The telephone will start vibrating at the moment of whistle detection.
- save battery: you can set listening out for the whistle only while the screen of the phone is off.
- Detection of incoming connection: This option will put the application on hold when the phone receives a call.
At the phone call end, the application will resume listening out for the voice signals.
- configure the microphone sensitivity. The effectiveness of whistle detection depends on built-in microphone and number of noises and sounds of surrounding.
- configure how the alert should stop. Should it stop at the voice signal end or should it continue until being stopped manually.
- configure signal minimum duration before triggering the alert.
- configure screen Brightness when alarm is on.

## Snapshots
<p>
<img src="./screenshots/Screenshot_1.png" width="250" height="444">
</p>
<p>
<img src="./screenshots/Screenshot_2.png" width="250" height="444">
</p>
<p>
<img src="./screenshots/Screenshot_3.png" width="250" height="444">
</p>
<p>
<img src="./screenshots/Screenshot_4.png" width="250" height="444">
</p>

## Change logs
### version 2.0 (Modernization Update)
* **MAJOR MODERNIZATION**: Updated to Android 13 compatibility
* Migrated from Support Library to AndroidX
* Added notification channels for Android 8.0+
* Enhanced runtime permissions for Android 13+
* Updated build system to modern Gradle and AGP
* Improved foreground service implementation
* Added modern backup and security features
* Compatible with Google Play Store requirements

### version 1.3
* Display stop alarm activity if manual alarm stopping is selected 
* wake up device when alarm is on
### version 1.2
* Add preference to maximize screen brightness and ringtone volume when alarm is on
### version 1.1
* Add preference in settings to control how to stop the alert: manually or on sound end
* add action in notification to stop the alert
* Add preference to control signal duration before triggering the alert
### version 1.0
* detect sound pitches
* add 3 alert types: flash, vibration and ringtone
* add save energy mode
* detect incoming calls and put application on hold during the call
* user can configure microphone sensitivity

## Special Thanks
* contributors to  [Parceler](http://parceler.org/) library
* contributors to [TarsosDSP](https://0110.be/tags/TarsosDSP) project
* @txusballesteros to his [snake](https://github.com/txusballesteros/snake) chart
