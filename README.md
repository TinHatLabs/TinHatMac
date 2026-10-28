# Tin Hat for Mac

Tin Hat for the Mac: your Tin Hat server's app in a Mac window, with notifications that work while Tin Hat is closed.
This repository holds the Mac releases; the app's source isn't published here (yet).

## Install
1. Download **TinHat-mac.dmg** from the [latest release](https://github.com/TinHatLabs/TinHatMac/releases/latest).
2. Open it and drag **Tin Hat** onto **Applications**, then open Tin Hat from Applications.
3. Type your server's name (like `crew`) or its address, and sign in.

Needs macOS 14 (Sonoma) or newer, on Apple silicon or Intel. The app is signed with the Tin Hat Developer ID and
notarized by Apple, so it opens without warnings.

## Updates
Tin Hat checks for a new version once a day and installs it when you quit (never during a call); **Tin Hat → Check for
Updates…** looks right away. Each update must carry two signatures before it's installed: Tin Hat's update key and
Apple's notarized Developer ID signature.

## Notifications when Tin Hat is closed
**Tin Hat → Notifications When Closed…** sets this Mac up once (your password, sent only to your server) and adds a small
background item, also called Tin Hat, that shows your messages while the app is closed — readable, also in encrypted
rooms. Turn it off in the same place.

## Check a download
Each release lists the SHA-256 of its files in `SHA256SUMS`:
`shasum -a 256 TinHat-mac.dmg`
