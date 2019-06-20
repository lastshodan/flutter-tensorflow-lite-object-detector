


## Overview

This mobile app is used to detect car spare parts images using the phone's camera.This code is unfinished.--part of the code is private(meant to be commercialized)

## Dependencies

All of these can be downloaded in a single command, see below. 

- MobileNet
- Tensorflow Lite
- Stripe
- RazorPay
- Flutter

## Instructions

First install [Flutter](https://flutter.dev/docs/get-started/install). 

After download, from command line run this to install the dependencies
```
flutter packages get
```
Then run this command to run the app

```
flutter run
```
Alternatively you can open the app as a new flutter project in Android Studio after installing the Flutter plugin. 

## TODO - please make a PR if you fix any of these

- Car spare parts sellers affiliate system to be integrated
- Firebase is integrated, but it still needs to be properly wired up to the login and signup pages.
- Stripe and RazorPay are integrated, but each still need to be wired up to the Credit/Debit Card view i created.
- MPESA payment to be integrated 
- Generate some text everytime a pose is detected, not just on startup.



## Credits

Thanks to [shaqian](https://github.com/shaqian/flutter_realtime_detection) for his starter code. 
