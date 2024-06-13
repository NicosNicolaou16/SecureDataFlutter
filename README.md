# Secure Data Flutter
This example project tested how we keep secure the data in Flutter, example, api key(s).

# Steps
1) Create the .env inside the main directory.
2) Create the env.dart file.
3) For static variable ```static String apiKey = _Env``` and run the new command (the old one deprecated) "dart run build_runner build" or dart run build_runner build --delete-conflicting-outputs.
4) Generated.
5) Add the Key ```static String apiKey = _Env.apiKey```.

### Important Note: 
For this example keeps the files with dummy/tested api key but for real project you have to add them in gitignore file.

### Commands for generation
dart run build_runner build or dart run build_runner build --delete-conflicting-outputs

## Versions

Flutter SDK version: 3.22.2 <br />
Dart Version: 3.4.3 <br />

# References
https://pub.dev/packages/envied <br />
https://medium.com/@r1n1os/securing-sensitive-data-in-flutter-d0a8e060a11e <br />
https://github.com/r1n1os/Secure-Sensitive-Data-Example <br />

