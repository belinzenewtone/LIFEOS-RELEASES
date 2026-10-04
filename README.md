# LifeOS releases

Signed Android builds of LifeOS and the small `manifest.json` the app reads to find them. No source code lives here.

The app checks `manifest.json` about once a day (switchable in Settings > App updates), downloads a newer APK only when its
checksum, package name and signing key match, and installs it only after the person taps Install.
