# Support control
Every iteration of SIF (SnapIntegrityFix) has its own folder, this folder must follow the Semantic versioning scheme.<br>
More about this [here](https://semver.org/).

The included versions in the text file `supported_versions.json` contained within the individual folder define which version(s) are confirmed to be working correctly.

This file may only use this specific format:
```json
{
  "12.x.x.x",
  "13.x.x.x",
  "14.x.x.x",
}
```
This file does not rely on newlines, they are not required for correct operation.
