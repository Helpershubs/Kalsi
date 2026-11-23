# KALSI Renewables mobile app

Starter Expo React Native project for Android and iOS.

## Run the project
1. Install Node.js LTS on a computer, or open the project in a compatible cloud development environment.
2. Run `npm install`.
3. Run `npx expo start`.
4. Scan the QR code with Expo Go to preview on a phone.

## Build an installable Android APK
1. Install EAS CLI: `npm install -g eas-cli`
2. Sign in: `eas login`
3. Configure the project: `eas build:configure`
4. In `eas.json`, keep the `preview` profile with `android.buildType` set to `apk`.
5. Run `eas build -p android --profile preview`.
6. Download the APK from the build page and install it on your Android phone.

## Important limitations
This is a runnable front-end starter. Enquiries are stored only in local app state and disappear when the app restarts. Authentication, central customer database, live admin permissions, payments, push notifications, maps, media uploads, AI assistant, real-time chat and server-side project tracking require backend services and configuration. Payment and account flows are not connected. Do not publish commercially until those services, privacy policy, business contact details and security rules are implemented and tested.

For iOS, use `eas build -p ios` with the required Apple developer signing/account setup. An Android APK cannot be installed on iPhone.
