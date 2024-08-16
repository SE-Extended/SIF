# What is SIF?
SIF (Snap Integrity Fix) is a native library developed by rhunk to remove some of Snapchat's security detections. It allows the use of modules such as [SnapEnhance](https://codeberg.org/SnapEnhance/SnapEnhance), but does not provide ban bypass solutions or emulators. It runs locally only and doesn't communicate with other third-party services, which means you don't need an Internet connection to use it properly. If you have any questions about this, join https://t.me/snapenhance_chat.

> **Note**
> The current builds are designed for testing device compatibility only and do not contain any fixes at the moment.

# Version control
The version string defined in the [`version`](https://codeberg.org/SnapEnhance/resources/blob/main/sif/version) file will decide which version of SIF is the latest one and will invalidate every single other build that does not match its version.

You may define one version, and one version only. Keep an eye out for unnecessary new lines.

The sole purpose for this is to prevent running outdated and detected software on the user side.

SIF may be temporarily shut down in the case of detection without fix by setting the version string to `TERM`.

The versioning follows MAJOR.MINOR.PATCH, which complies with the semantic versioning scheme. <br>You may find more information about this [here](https://semver.org/).
