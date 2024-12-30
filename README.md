# Secure Data Flutter

This example project tests how we secure data in Flutter, such as API keys.

# Steps

1) Create the `.env` file inside the main directory.
2) Create the `env.dart` file.
3) For static variable ```static String apiKey = _Env``` and run the new command (the old one
   deprecated) "dart run build_runner build" or dart run build_runner build
   --delete-conflicting-outputs.
4) Generated.
5) Add the Key ```static String apiKey = _Env.apiKey```.

### Important Note:

For this example, keep the files with dummy/test API keys, but for a real project, you should add
them to the .gitignore file.

### Commands for generation

`dart run build_runner build or dart run build_runner build --delete-conflicting-outputs`

## Versioning

Flutter SDK version: 3.24.4 <br />
Dart Version: 3.5.4 <br />

# References

https://pub.dev/packages/envied <br />
https://medium.com/@r1n1os/securing-sensitive-data-in-flutter-d0a8e060a11e <br />
https://github.com/r1n1os/Secure-Sensitive-Data-Example <br />

