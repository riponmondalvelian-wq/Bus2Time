BUS2TIME ANDROID APP — V1
===========================
This is an Android Studio project wrapping the same Bus2Time UI as the browser prototype
inside a native Android WebView shell.

Included:
- Same Bus2Time logo and blue design
- Raju Travels / WB51A1165 data
- Up/Down timetable
- From -> To search
- Route and stops
- Favourites
- Local Admin Panel
- Add/edit/delete bus
- Add/edit/delete stops and times
- JSON backup import/export

How to build:
1. Install Android Studio.
2. Open this folder as an existing project.
3. Let Gradle sync.
4. Run on an Android phone/emulator for testing.
5. For Play Store, create a signed Android App Bundle (.aab) using Android Studio's
   Build > Generate Signed Bundle / APK.

Production note:
V1 stores timetable changes locally on the device. Before Play Store launch,
connect the Admin Panel and user app to an online database with authentication so
new buses/timetables can sync to every user's device.
