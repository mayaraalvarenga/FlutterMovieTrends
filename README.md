[![Movie Trends](https://i.imgur.com/4buzRAQ.png)](https://github.com/mkiisoft/FlutterMovieTrends)

# Movie Trends - Flutter [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/mkiisoft/FlutterMovieTrends) [![GitHub version](https://d25lcipzij17d.cloudfront.net/badge.svg?id=gh&type=6&v=1.0&x2=0)](https://github.com/mkiisoft/FlutterMovieTrends)

Movie Trends it's an example using Flutter for Android and iOS.

# Execute

For the TheMovie Db you need to create a file called "keys.dart" over "/lib/utils/" and add the following with your key: 

```
part of app_movie;

class Keys {
  static final apiKey = 'YOUR API KEY';
}
```
To generate a new key you must create an account over [TheMovieDb](https://www.themoviedb.org/faq/api) and clicking the "API" link from the left hand sidebar within your account settings.

For Firebase, add your files under:
```
android/app/google-services.json
ios/Runner/GoogleService-Info.plist
```

For signing the APK you need to create a file under:
```
android/key.properties
```

with the following dat:
```
keyAlias="your key alias"
storePassword="your store password"
keyPassword="your key password"
storeFile="path of you .keystore"
```
Your keystore goes under 
```000
android/app/yourkey.keystore
```

# Features

* Firebase
* Login Screen
* Loading Screen
* Grid and List views
* Nested Scroll views
* Pagination
* TheMovie Db API
* Async tasks
* Custom Views
* Utils / Date formats
* Intent Uri launcher

## Getting Started

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).

# © 2018 Mariano Zorrilla
