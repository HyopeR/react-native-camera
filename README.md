# REACT NATIVE PLANET CAMERA 🪐

This package has been forked from the react-native-camera package.

**Reasons:**</br>
**1-** The react-native-camera package is not being continued.</br>
**2-** Alternative packages do not fully meet the need.</br>
**3-** The latest version of the current package does not meet the requirement.

**What does it do?**</br>
**1-** It uses **Google Mlkit** for Android platform.</br>
**2-** It uses **Firebase Mlkit** for Ios platform.

**Why?**</br>
After react-native-camera package migrated to Google Mlkit. Barcode scanning / Text scanning and Face detection operations on the Ios platform are not properly executed.

**CAUTION:**</br>
A firebase package included in your project should have a maximum version of 8.4.7. After the 9.0.0 migration, conflicts occur on the IOS side.

`@react-native-firebase/app: 8.4.7`
