# Secure Data Flutter
This example project tested how we keep secure the data in Flutter, example, api key(s).

# Steps (Solution for an issue)
1) Create the .env inside the main directory
2) Create the env.dart file
3) For static variable ```Dart static String apiKey = _Env``` and run the new command (the old one deprecated) "dart run build_runner build" or dart run build_runner build --delete-conflicting-outputs
4) Generated
5) Add the Key ```Dart static String apiKey = _Env.apiKey```

Note: For this example keeps the files with dummy/tested api key but for real project you have to add them in gitignore file

### Commands for generation
dart run build_runner build or dart run build_runner build --delete-conflicting-outputs

## Versions

Flutter SDK version: 3.16.5 <br />
Dart Version: 3.2.3 <br />

# Reference
https://pub.dev/packages/envied <br />
https://medium.com/@r1n1os/securing-sensitive-data-in-flutter-d0a8e060a11e <br />
https://github.com/r1n1os/Secure-Sensitive-Data-Example <br />

