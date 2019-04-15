# FreePusher
Application to test FCM push notifications

### How to play with it?
- add your `google-services.json` to the `app` directory
- change `applicationId` to your own (you can find it in the `google-services.json` by `package_name` keyword)
- sync the project
- execute `./gradlew clean aR` in the project root directory
- execute `adb install app/build/outputs/apk/release/app-release.apk` (if you have `adb`)
