# android-9.0-expo-scroll-bug

The page has a scroll view with 100+ images. Everything works fine for android 8.x and 7.x but video cannot scroll smoothly on android 9.0

## Reproduce steps
1. `expo init`
2. Choose blank project
3. Edit App.js .
4. Change <View> to <ScrollView>
5. Add 100 different images under the <ScrollView> for example https://github.com/gsunsnackv/android-9.0-expo-scroll-bug/blob/master/App.js
6. `yarn start` (this opens the expo page)
7. Open an Android emulator with Android 9.0 (Pie) installed
8. Click 'Run on Android device/emulator' on the expo page

## Expect
Expect to scroll smoothly

## Actual
Cannot scroll smoothly

## Notes
Audio is fine. And on Android 8.x and 7.x, everything is fine
