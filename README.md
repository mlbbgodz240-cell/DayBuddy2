# DayBuddy for Android

A cute, offline-first Android app for date-based celebrations, upcoming special days, personal dates, and daily notifications.

## Features
- Shows today's celebrations based on the device date.
- Curated calendar of common Indian and international dates.
- Upcoming celebration list.
- Add personal annual dates such as birthdays and anniversaries.
- Enable/disable daily notifications and choose a reminder time.
- Notification schedule is restored after device restart.
- Personal dates and settings are stored locally on the device.

## Build and install
1. Install Android Studio on a computer.
2. Extract this folder and open the `DayBuddy` folder in Android Studio.
3. Allow Android Studio to install the Android SDK and Gradle components it requests.
4. Connect an Android phone with USB debugging enabled, or use an emulator.
5. Press **Run** to install the app. To create an APK, choose **Build > Build APK(s)**.

The app uses Android SDK 35 and requires Android 8.0 (API 26) or later. An internet connection may be needed the first time Android Studio downloads build components; the app itself is designed to work offline.

## Notifications
- Android 13 and newer require notification permission. DayBuddy asks for it when opened.
- Reminders use Android's inexact repeating alarm, so battery management and Android scheduling can delay a reminder a little.
- If reminders do not arrive, allow notifications for DayBuddy and check the phone's battery/background restrictions.
- Daily reminder time uses the phone's local time zone.

## Calendar accuracy note
Special-day calendars vary by country and source, and social-media celebration days can be unofficial or disputed. DayBuddy includes a small curated set rather than claiming to cover every observance. You can add any date you want, including a locally popular Best Friend Day.
