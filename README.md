# Carryfood Offer Maker (Android)

An editable UAE supermarket offer-poster starter app. The default layout follows the supplied Carry Food Rigga reference: white page, green border/header, yellow product label and large red AED price.

## Features
- Edit supermarket name, product name, weight and AED price
- Pick a product photo from the phone
- Live poster preview
- Save a JPEG to Pictures/CarryfoodOffers
- Share the poster using Android's share sheet

## Build an APK
1. Open this project in Android Studio on a computer, or upload the repository to GitHub.
2. Use JDK 17 and Android SDK 36.
3. Run `./gradlew assembleDebug` (or select Build > Build APK(s) in Android Studio).
4. The debug APK is at `app/build/outputs/apk/debug/app-debug.apk`.

A GitHub Actions workflow is included to build the debug APK in the cloud after you push this project to a GitHub repository.
