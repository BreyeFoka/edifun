# EdiFun

A gamified education app built in Flutter as a team project: learners sign up, take courses, earn badges and track their progress.

## Features

- Sign-up, login and password reset with Firebase Authentication, plus terms of use
- Courses, with downloadable content for offline study
- Badges and a progress summary on the home screen
- Announcements, profile and settings

User data lives in Cloud Firestore.

## Run it

```bash
flutter pub get
flutter run
```

The Android build reads its Firebase project from `android/app/google-services.json`. To use your own project, replace that file (and set up iOS and web with `flutterfire configure`).

## Checks

GitHub Actions runs `flutter analyze` on every push. There are no automated tests yet, since every screen depends on Firebase being initialised.

## Credits

Built with [Zolender](https://github.com/Zolender) ([original repo](https://github.com/Zolender/Edifun)).
