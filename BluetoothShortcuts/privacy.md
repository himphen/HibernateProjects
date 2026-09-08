# Privacy Policy for BT Shortcuts

**Effective date:** 2026-09-08

BT Shortcuts ("the App", also referred to as "Bluetooth Shortcuts") is provided by Hibernate ("we", "us", or "our"). This Privacy Policy explains how information is handled when you use the App.

Please replace the bracketed placeholders in this policy before publishing it.

## Summary

- The App does not require an account.
- The App's core shortcut features work locally on your Android device. We do not operate a server that receives your Bluetooth configuration.
- The App stores shortcut configuration, including selected paired-device details and selected apps, in the App's private local storage.
- The App may use Google Mobile Ads and Google Firebase Crashlytics. These services may process information according to their own policies.
- Google Play processes payments for the optional one-time purchase that removes ads.

## Information handled by the App

### Bluetooth and nearby-device information

When you grant the Android nearby-devices/Bluetooth permission, the App:

- reads the Bluetooth devices already paired with your device so that you can choose one;
- observes Bluetooth connection and disconnection events; and
- stores the selected device's Bluetooth identifier and display name locally so it can match connection events to your shortcut rules.

The App does not perform Bluetooth discovery or scanning and does not request Android location permission for this feature. Bluetooth identifiers and names are not sent to our server by the App's core functionality.

### Selected apps and shortcut configuration

The App lists launchable apps on your device so that you can select up to three apps for a Bluetooth shortcut. It may locally store the selected apps' package names, activity names, and labels, together with your enabled/disabled shortcut rules.

The App does not use `QUERY_ALL_PACKAGES`. The app list and shortcut configuration are used locally to display choices and open the apps you select.

### Preferences and temporary connection state

The App stores certain preferences locally, such as:

- notification style;
- whether the introduction has been viewed; and
- whether the local device has an active remove-ads entitlement.

Temporary connection-session state is also stored locally to prevent duplicate notifications. It is discarded when it is no longer valid, including after an Android reboot.

### Notifications

If you grant notification permission, the App creates local Android notifications containing shortcut actions when a configured paired device connects. The App does not send these notifications through a separate notification server.

## Advertising and consent

The App may display a banner advertisement on the Home screen. It uses the Google Mobile Ads SDK and Google User Messaging Platform (UMP). Where required, UMP asks for your consent before ads are initialized or personalized.

Depending on your location, consent choices, device settings, and Google's processing, Google may process information such as an IP address, advertising or other device identifiers, device and app information, approximate location derived from an IP address, ad interactions, and diagnostic information to provide, measure, and protect advertising services. The exact information and purposes are controlled by Google and the applicable consent choices.

You can manage available ad-consent choices through the controls presented by the App or your Android device. A one-time Google Play purchase can remove the App's Home banner; the purchase does not remove information already processed by Google.

For more information, see Google's [Privacy Policy](https://policies.google.com/privacy) and [information about how Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites).

## Crash reports and diagnostics

Release builds may use Firebase Crashlytics to help us identify and fix crashes and other stability problems. Crashlytics may automatically process information such as crash reports, stack traces, app and device information, operating-system information, and diagnostic data.

BT Shortcuts does not intentionally add Bluetooth addresses, Bluetooth device names, or selected app lists as custom Crashlytics fields. Crashlytics collection is disabled in debug builds.

Firebase Crashlytics is provided by Google. See [Firebase's privacy and security information](https://firebase.google.com/support/privacy) for more information about Firebase data processing.

## Purchases

The optional remove-ads purchase is processed by Google Play Billing. Google may process your Google Play account, payment, purchase, and transaction information under Google's terms and privacy policies. We do not receive or store your payment-card details.

The App stores only a local entitlement flag so it can determine whether to display the Home banner. Google Play remains responsible for payment processing, refunds, and purchase-account records.

## Feedback and external links

If the App provides a feedback link, it opens an external website or form in your browser. Any information you submit there, such as your email address, device details, or message, is collected by the provider of that website and is governed by that provider's privacy policy. Please do not include sensitive information unless it is necessary.

The App may also open Android settings or another app you select. Once you leave the App, the destination's privacy practices apply.

## Information we do not intentionally collect

The App does not require you to provide your name, postal address, phone number, or account credentials. We do not intentionally collect contacts, photos, precise location, microphone recordings, camera data, or the contents of your messages through the App.

We do not sell your personal information. Information may nevertheless be processed or shared by service providers such as Google Mobile Ads, Firebase Crashlytics, and Google Play as described above.

## Storage, retention, and deletion

The App stores its core configuration in private Android app storage. The App's local data is excluded from Android cloud backup and device transfer by its Android backup rules.

You can delete local App data at any time by:

1. removing configured devices and shortcut rules in the App;
2. using Android Settings to clear the App's storage; or
3. uninstalling the App.

Clearing storage or uninstalling the App removes local shortcut configuration and preferences, subject to Android and Google Play behavior. We do not have a server-side account containing the App's core Bluetooth configuration.

Crash reports, advertising information, consent records, and purchase records are retained by Google or other applicable providers according to their policies and retention practices. To request access to or deletion of information held by one of those providers, use the provider's privacy controls or contact that provider. You may also contact us and we will assist where we reasonably can.

## Security

We use reasonable measures, including Android's app-private storage and limiting the App's data collection, to protect information handled by the App. No storage or transmission method is completely secure, and we cannot guarantee absolute security.

## Children's privacy

The App is not directed to children under 13, and we do not knowingly collect personal information from children under 13. If you believe a child has provided personal information to us, please contact us so we can take appropriate action. If your local law defines a different minimum age, that age applies.

## Your privacy rights

Depending on where you live, you may have rights to access, correct, delete, restrict, object to, or obtain a copy of personal information processed about you, and to withdraw consent where processing is based on consent. You can exercise local App-data choices using the controls described above. For requests concerning information processed by Google or another provider, that provider may be the appropriate party to contact.

## Changes to this policy

We may update this Privacy Policy when the App or its data practices change. We will post the updated policy at the same public location and update the effective date above. Your continued use of the App after an update means the updated policy applies to your use of the App, to the extent permitted by law.

