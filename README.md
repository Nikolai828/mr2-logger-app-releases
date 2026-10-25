# MR2 Logger app: debug builds

APK only: no source, no designs, no data. Install over a previous build and your logs and settings stay
(all builds use the same signing key). Built from commit `ba53df7` of the private source repository.
These are developer builds: they include a "Save to Downloads" action for logs that the public release will not have.

| File | For | SHA-256 |
|---|---|---|
| `mr2.apk` | phones (64-bit ARM, Android 7+) | `458534b2474902fcc6f97656dc9c2797757ef1adf3e290cd77098d967f6ec126` |
| `mr2-unit.apk` | 32-bit ARM head units (ARMv7), Android 7+ | `fddc8be0b8d3dac34105932e1afbdbb0965d8e4dda6e5bbe40094372859e509c` |

The head-unit build runs the same app on Python 3.11. Live, Mark and the checks list do not use Python; the log
analysis does, and is slow on a 32-bit unit: analyse logs on the phone.

<!-- apks:begin (written by android/scripts/publish-apks.sh: do not edit by hand) -->

Latest build `7ac9549`, built 2026-10-25T20:07:04Z. A queued log download no longer blocks an app update; cylinder labels hold 30 s

| File | For | Python | Size | SHA-256 |
|---|---|---|---|---|
| `mr2.apk` | 64-bit ARM phones | Python 3.13 | 70.6 MB | `17cddde53ae8b9cfa88eecaa78ce69fdba1bab90b9ff2f3297d713fc67269c22` |
| `mr2-unit.apk` | 32-bit ARMv7 head units | Python 3.11 | 70.2 MB | `71d884dc2575f163ac5aaea8c03091606f25e9d729982a86585140e7a9c2a906` |

<!-- apks:end -->
