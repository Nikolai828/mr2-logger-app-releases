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

Latest build `81c59bf`, built 2026-10-24T17:47:31Z. Live mirror, 3 Mbaud link, storage limit, live trace, in-app updates, IGT fix

| File | For | Python | Size | SHA-256 |
|---|---|---|---|---|
| `mr2.apk` | 64-bit ARM phones | Python 3.13 | 70.4 MB | `644443ae5ade4592e13f3d413d75443341a998966658ccec09bb92ef9bcf304e` |
| `mr2-unit.apk` | 32-bit ARMv7 head units | Python 3.11 | 70.0 MB | `86caa62965cc62043bd1a06053674c6dc75a4f8cfa2fd3e65f988b6e8f7bfb77` |

<!-- apks:end -->
