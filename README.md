# Secure Data Flutter
This example project tested how we keep secure the data in Flutter, example, api key(s).

# Steps (Troubleshooting)
1) Create the .env inside the main directory
2) Create the env.dart file
3) For static variable ```Dart static String apiKey = _Env``` and run the new command (the old one deprecated) "dart run build_runner build" or dart run build_runner build --delete-conflicting-outputs
4) Generated
5) Add the Key ```Dart static String apiKey = _Env.apiKey```

# Reference
https://pub.dev/packages/envied <br />
https://medium.com/@r1n1os/securing-sensitive-data-in-flutter-d0a8e060a11e <br />

