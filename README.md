# Mumbai Auto Mart — Flutter starter app

A cross-platform Flutter starter for an owner-managed car and bike showroom app. It includes a premium home screen, search, Cars/Bikes filters, vehicle cards, vehicle details, and call/WhatsApp enquiry buttons.

## Before using it for real

1. Replace `contactNumber` in `lib/main.dart` with your real business phone number in international format, e.g. `+919876543210`.
2. Replace the sample/demo vehicles in `vehicles` with vehicles you actually have for sale. Current prices, specs and photos are sample content and must not be treated as real inventory.
3. The app currently uses sample data embedded in the app. A secure admin panel and cloud database are not yet connected; those are needed to add/edit/remove listings without updating the app.
4. Check image licensing and use photos you own or have permission to use before publishing.

## Run locally

Install Flutter and Android Studio (for Android) and/or Xcode on a Mac (for iOS), then from this folder run:

```bash
flutter pub get
flutter run
```

## Build

Android APK:

```bash
flutter build apk --release
```

iOS build (requires macOS and Xcode):

```bash
flutter build ios --release
```

This is the source project, not a signed installable app or published store listing. Store publication requires developer accounts, app identifiers, signing, privacy details, and testing.
