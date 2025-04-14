# ppb_assignment2
# Used Car Dealership using ObjectBox as local database

![image](https://github.com/user-attachments/assets/716ea94c-3c11-4fe5-9731-ed21f994dc8b)


# Features ⚙️
- CRUD
- Saving data to local storage

# Requirements 💻 
- Flutter SDK v3.7.0 or above
- Dart SDK
- ObjectBox dependencies

# Project Structures

![image](https://github.com/user-attachments/assets/64c0ab11-e3c2-4e77-bd9c-06be2f6edad6)


# yaml Dependencies
<pre> dependencies: 
  objectbox: ^4.1.0 
  objectbox_flutter_libs: any 

dev_dependencies:
  build_runner: ^2.0.0
  objectbox_generator: any
</pre>

`flutter pub get`

`flutter pub run build_runner build`

**App can be run! 🎉**

# File explanation

`car_model.dart`

Use to represent an entity of a car in this program.

`objectbox_helper.dart`

Work as controllor for the ObjectBox database

# Note

This program can't use the admin localhost, so restart your app and relaunch to see if it's work or not. If it's work, the data you've craeted on the apps would appear.
