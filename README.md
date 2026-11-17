# NightBell — Android alarm clock

A minimal dark Android alarm app with multiple one-time alarms, enable/disable, delete, default alarm tone, snooze for five minutes, and alarm restoration after reboot.

## Build an APK without a laptop
1. Create a GitHub account if needed.
2. Create a new repository and upload the contents of this ZIP.
3. Open the repository's **Actions** tab and run **Build NightBell APK** (or push the files).
4. Open the completed workflow run and download the `NightBell-debug-apk` artifact.
5. Extract the artifact and install `app-debug.apk` on your Android phone.

## Android setup
After installing, open NightBell and allow notifications. When adding an alarm, Android may ask you to allow exact alarms. Enable that permission for reliable timing. Also allow full-screen notifications if Android offers that setting.

## Notes
- Alarms are one-shot; add another alarm if you want another occurrence.
- Android battery management varies by manufacturer. Do not force-stop the app; check battery restrictions if alarms are delayed.
- This is a starter project, not a Play Store release. Test with a near-future alarm before relying on it.
