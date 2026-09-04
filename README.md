# Femme Fast

Fasting that fits your life, pill alarms that actually ring, and a cycle, weight and drinks
tracker that understand each other. A personal wellness app for Android and iPhone, with a
web companion.

**Website:** https://femmefast.vercel.app/

## Download the latest version

| Platform | Get it |
|---|---|
| **Android** | [Download FemmeFast.apk](https://github.com/pmae8/femme-fast-releases/releases/latest/download/FemmeFast.apk) |
| **iPhone** | [Download FemmeFast-unsigned.ipa](https://github.com/pmae8/femme-fast-releases/releases/latest/download/FemmeFast-unsigned.ipa) and install with [SideStore](https://sidestore.io/) (recommended) or [Sideloadly](https://sideloadly.io/) from a Windows or Mac computer |

These links always point at the newest release, so they never go stale.

### Android install notes

1. Open the APK link on the phone. Chrome will ask once to allow installs from this source.
2. If Play Protect asks to scan the app, let it - the app scans clean.
3. Tap **Install**. Installing over an older version keeps your data.

Once installed, the app checks for updates itself and offers to download and install the next
version in-app.

### iPhone install notes

Femme Fast is not on the App Store. It is installed by sideloading, and the installer you
pick decides what works:

| Installer | App and real alarms | Lock-screen card (Live Activity) | Weekly refresh |
|---|---|---|---|
| [SideStore](https://sidestore.io/) (recommended) | yes | yes | on the phone, no computer |
| [Sideloadly](https://sideloadly.io/) | yes | no - it cannot sign the extension | computer needed |

**SideStore**

1. On the iPhone, install LocalDevVPN from the App Store.
2. On a Windows or Mac computer, install iloader from the SideStore docs and connect the iPhone by cable.
3. Sign in with your Apple ID in iloader and choose Install SideStore.
4. On the phone, trust the developer profile under Settings > General > VPN & Device Management, connect LocalDevVPN, open SideStore and sign in.
5. Download the IPA above in Safari, then in SideStore tap My Apps > + and pick it.

**Sideloadly**

1. Install Sideloadly on a Windows or Mac computer and download the IPA above.
2. In Advanced Options, untick "Use automatic bundle ID" and keep `com.maevamobile`.
3. Connect the iPhone, sign in with your Apple ID, and install.

Real pill and fast-end alarms need iOS 26 or newer. With a free Apple ID the install expires
after 7 days; SideStore refreshes it from the phone, Sideloadly needs the computer again.

## What is in this repo

Only releases. Each release carries the Android APK, the iPhone IPA and `latest.json`, the
manifest the app reads to know a newer version exists. The app's source code is private.
