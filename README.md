# mobile_number_picker

Note: It works for Android only because getting mobile number is not supported in iOS.

Usage

Call Function to inflate the mobile picker dialog
```dart
    mobileNumber.mobileNumber();
```dart

Listen to stream to listen to events added to stream
```dart
 mobileNumber.getMobileNumberStream.listen((event) {});
 ``dart