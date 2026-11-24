# RustCON Privacy Policy

Updated November 24, 2026 · xADROCx / Shadow Kids Studios

RustCON lets authorized administrators manage their Rust game servers. This policy describes the iOS app, including earlier iOS versions where noted.

## Your servers and device data

RustCON sends the RCON password directly to the server you configure to authenticate the connection. Commands, chat broadcasts and server replies travel between your device and that server. Standard WebRCON is unencrypted. Update 3 supports TLS when your RCON endpoint offers it. Server operators and hosting providers control what their servers log and retain.

Update 3 saves server profiles and passwords in the iOS Keychain on the device. Earlier versions saved them in local app storage. Settings, recent Rust chat, imported map or kit images and cached artwork are stored on the device. The game chat archive can contain player display names, Steam IDs, timestamps and messages. Player map coordinates are positions inside the game world received from your authenticated server connection. RustCON does not request your GPS location.

In versions with Player log, RustCON uses data from your configured server to show player logins and logouts, a count of logins observed by RustCON and session lengths when available. Entries can contain player display names, Steam IDs and event timestamps. Chat and player activity are stored on your device for use by authorized server administrators.

In Chat, open **History** and choose **Delete history** to erase the selected server’s saved chat and player activity from this device and reset its local login counts. **Clear chat** temporarily hides the timeline. Use **Export log** to save a separate file that can contain the server address and the archive’s contents. You control where you save or share that file. Manage exported copies and records kept by your server separately.

You can remove a saved server in RustCON or delete the app to remove its local settings and chat archive.

## Purchases, avatars and map artwork

- **Apple and RevenueCat.** Apple processes payments. RevenueCat processes purchase and subscription history, an app-generated customer ID and receipt information to verify access and support purchase restoration. RustCON does not collect payment card details. [Apple Privacy Policy](https://www.apple.com/legal/privacy/) · [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy/)
- **Steam.** RustCON uses public Steam IDs from the server to look up public profile images. Earlier versions can use a third-party proxy for these public lookups. [Valve Privacy Policy](https://store.steampowered.com/privacy_agreement/)
- **Server map terrain.** In map-enabled versions, RustCON can query your configured server for its published terrain-image URL and download that image over HTTPS from Facepunch. Facepunch receives ordinary network request information such as your IP address. Player coordinates and RCON passwords are not included in that image request. You may also import a map image on your device.
- **Artwork and item catalog.** Update 3 requests item catalog data and draws the category icons locally. Earlier versions may request item images. The app may load banner, kit or terrain images from hosts specified by a server. Those hosts receive the network request and can see ordinary request information such as your IP address. Only use artwork sources you trust.

RustCON does not sell personal data or use it for targeted advertising. Apple may make crash reports available to the developer according to your device settings. If you email support, we use the information you provide to respond and resolve the issue.

## Earlier versions and retained data

Earlier iOS versions offered hosted Admin Chat. Firebase received a server-derived identifier, an installation ID and presence information during connections. It also stored messages, display names and timestamps when administrators used that feature. Update 3 no longer uses Firebase. Records from previous versions may remain until removed. Contact support if you need access to or deletion of those records. [Google Privacy Policy](https://policies.google.com/privacy)

RevenueCat, Apple and other providers handle retention for the services they operate. We retain support correspondence as needed to respond, resolve disputes and meet legal obligations. To request access, correction or deletion of data we hold, or to ask about your privacy rights, email [support@shadowkidsstudios.com](mailto:support@shadowkidsstudios.com). Please leave passwords and API keys out of your request.

RustCON is intended for server administrators and is not directed to children under 13. Policy changes are posted here with the update date.

## Terms and support

The iOS app is subject to [Apple’s Standard Licensed Application End User License Agreement](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/). For billing, use [Apple subscription settings](https://apps.apple.com/account/subscriptions). For RustCON support or to report abuse, email [support@shadowkidsstudios.com](mailto:support@shadowkidsstudios.com).
