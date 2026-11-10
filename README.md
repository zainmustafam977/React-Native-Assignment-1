# MuhammadZain — React Native Setup (Assignment 1)

**Course:** Mobile Application Development (MAD) — University of Management and Technology (UMT), School of Systems and Technology (SST)
**Instructor:** M. Shahbaz Ali
**Assignment:** 1 (Total Marks: 20)

A brand-new React Native project created and run on the Android Emulator as proof of a working development setup.

- **React Native:** 0.88.1
- **React:** 19.3.0
- **App name:** `MuhammadZain`
- **Android package:** `com.muhammadzain`
- **Emulator:** `Medium_Phone_API_37.0` (Android 15 / API 37, x86_64)
- **Node:** >= 22.11.0

## Proof of setup

| File | What it shows |
| --- | --- |
| `emulator-proof.png` | The app running on the Android Emulator (default React Native welcome screen) |
| `structure-proof.png` | The project folder structure |

## Project structure

```
.
├── android/                 Android native project (Gradle, Kotlin)
├── ios/                     iOS native project (Xcode)
├── __tests__/               Jest tests
├── App.tsx                  Root component
├── index.js                 App registration entry point
├── app.json                 App name / display name
├── metro.config.js          Metro bundler configuration
├── babel.config.js          Babel configuration
├── package.json             Dependencies and scripts
├── emulator-proof.png       Screenshot: app running on the emulator
├── structure-proof.png      Screenshot: project structure
└── README.md
```

## How to run

```bash
# 1. Install dependencies
npm install

# 2. Start an Android emulator (or connect a device)
#    e.g. from Android Studio > Device Manager, or:
emulator -avd Medium_Phone_API_37.0

# 3. Build, install and launch the app on the emulator
npm run android
```

Metro starts automatically with `npm run android`. To start it manually in a separate terminal:

```bash
npm start
```

## Other scripts

```bash
npm run lint   # ESLint
npm test       # Jest
```

## Links

- React Native documentation: https://reactnative.dev/docs/getting-started
- Environment setup: https://reactnative.dev/docs/set-up-your-environment
