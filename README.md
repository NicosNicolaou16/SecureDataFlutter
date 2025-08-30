# Secure Data Flutter

[![Linktree](https://img.shields.io/badge/linktree-1de9b6?style=for-the-badge&logo=linktree&logoColor=white)](https://linktr.ee/nicos_nicolaou)
[![Static Badge](https://img.shields.io/badge/Site-blue?style=for-the-badge&label=Web)](https://nicosnicolaou16.github.io/)
[![X](https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white)](https://twitter.com/nicolaou_nicos)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nicos-nicolaou-a16720aa)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@nicosnicolaou)
[![Mastodon](https://img.shields.io/badge/-MASTODON-%232B90D9?style=for-the-badge&logo=mastodon&logoColor=white)](https://androiddev.social/@nicolaou_nicos)
[![Bluesky](https://img.shields.io/badge/Bluesky-0285FF?style=for-the-badge&logo=Bluesky&logoColor=white)](https://bsky.app/profile/nicolaounicos.bsky.social)
[![Dev.to blog](https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)](https://dev.to/nicosnicolaou16)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://www.youtube.com/@nicosnicolaou16)
[![Static Badge](https://img.shields.io/badge/Developer_Profile-blue?style=for-the-badge&label=Google)](https://g.dev/nicolaou_nicos)

This example project tests how we secure data in Flutter, such as API keys.

# Steps

1) Create the `.env` file inside the main directory.
2) Create the `env.dart` file.
3) For static variable ```static String apiKey = _Env``` and run the new command (the old one
   deprecated) `dart run build_runner build` or
   `dart run build_runner build--delete-conflicting-outputs`.
4) Generated.
5) Add the Key ```static String apiKey = _Env.apiKey```.

### Important Note:

For this example, keep the files with dummy/test API keys, but for a real project, you should add
them to the `.gitignore` file.

### Commands for Generation

`dart run build_runner build` or `dart run build_runner build --delete-conflicting-outputs`

## Versioning

Flutter SDK version: 3.35.2 <br />
Dart Version: 3.9.0 <br />

# References

https://pub.dev/packages/envied <br />
https://medium.com/@r1n1os/securing-sensitive-data-in-flutter-d0a8e060a11e <br />
https://github.com/r1n1os/Secure-Sensitive-Data-Example <br />

