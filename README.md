# Removing Backup Data from Flutter Application:

By default, Flutter applications store backup data in the local storage. However, you can ensure that this data is removed by following these simple steps:

1. Disable Backup Data Storage:

Open the AndroidManifest.xml file located in the android/app/src/main directory of your Flutter project.
Add the attribute android:allowBackup="false" to the <application> tag.
This step ensures that the application's data won't be backed up when the app is uninstalled.

![Screenshot 2024-03-27 at 10 01 31 AM](https://github.com/EftiarHKhan/Flutter-cache-remove-by-uninstalling-the-app/assets/105238792/5f715048-6338-4534-a517-4666db5d9d51)


![Screenshot 2024-03-27 at 10 02 13 AM](https://github.com/EftiarHKhan/Flutter-cache-remove-by-uninstalling-the-app/assets/105238792/a342d11f-4a5a-4a19-8936-ba3207103c37)


2. Clearing Cache and Data:

After making the above change, reinstall the app on your device.
Then, uninstall the app from your device.

This action ensures that any previously stored backup data associated with the app is cleared from the device's storage.
Following these steps will help ensure that no backup data is retained in the local storage of your Flutter application.
