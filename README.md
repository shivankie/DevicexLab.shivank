# DeviceLab X v1

Android diagnostic/security app.

## Included
- Dashboard
- Device identity and Android information
- RAM/storage/display information
- Root indicators
- `su` binary checks
- test-key/build-type checks
- SELinux status
- Developer Options / USB debugging status
- Risk score
- Anti-evasion indicator summary
- Performance snapshot

## Build
Open the project in Android Studio and let Gradle sync. Then run the `app` configuration on an Android device/emulator.

## Notes
The security scanner is diagnostic only. It does not modify the device, hide root, spoof integrity, or bypass another application's security controls.
