# Prism Relay 1.0 test build

Native Android mirror-routing puzzle. Tap mirrors to turn the beam, light numbered relay beacons in order, and reach the receiver on the right. Ten handmade circuits. No timer: inspect, rotate and retry at your pace.

GG 007 Gaming menu/icon, studio link, accurate privacy notice, saved Cyan Circuit/Amber Dusk beam style and relay-number visibility. Numbers are on by default. All puzzles can be selected independently; completed circuits are marked locally.

Android 8+ / API26 minimum, target35. Native Java/Canvas, not a web wrapper. No requested permissions, network access, ads, analytics or third-party SDKs. Website button opens the external browser. Clear app data/uninstall to remove local preferences and completion records.

## Build
JDK17, Android SDK platform35 and build-tools35.0.0, zip. Run ./build.sh with ANDROID_HOME. For signing, set private KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE plus KEY_ALIAS. Signing material is not part of this source.

## Tests and limits
BoardTest enumerates all mirror configurations in each puzzle and confirms at least one complete ordered-relay path, ten initially unsolved boards, and reflection reversibility. Actual native drawing/input code was also exercised under a local Java2D adapter: menu/settings/privacy, puzzle selection, touch rotation, win/next and saved settings. Rendered menu/settings/privacy/easy/hard puzzle pixels inspected. These are code/layout tests, NOT Android phone performance or touch/runtime certification. This is a signed TEST APK, not a final release or Google Play publication. Phone checks remain needed.

## Factory difference
Tetherwake uses continuous real-time tether/release momentum. Prism Relay is a discrete grid beam trace with ordered beacon validation and exhaustive configuration tests. The catalog's BankShot is a one-cushion aim calculator, not a playable relay circuit. No claim that the broad mirror-puzzle genre is new.

## Test download

https://mega.nz/file/IQ13waxJ#VU9frptEgK39_M_8tol2JE9UveteFpq4yffP420Lqmo

SHA256: `730bf4565e4e5f9ed64d9cfbe7a34d3b4dc8f3bffe9196f823d9bccab4d453c4`

Full source is preserved privately while repository source upload is pending. The APK is not hosted in this repository.
