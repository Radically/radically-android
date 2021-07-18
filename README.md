# Radically for Android

Generated using [Bubblewrap](https://github.com/GoogleChromeLabs/bubblewrap). 

The current purpose of this app is to improve discoverability by uploading it to the Play Store.

## Notes
- For a [TWA to launch successfully](https://developer.chrome.com/docs/android/trusted-web-activity/overview/), the SHA256 fingerprint of the signing certificate must be added to `/.well-known/assetlinks.json`. Otherwise, it falls back to Chrome Custom Tabs, and the URL bar is visible.
- The deployed version of Radically has Digital Asset Links added during the CD process.
