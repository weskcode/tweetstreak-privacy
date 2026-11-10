# TweetStreak Privacy Notice

Effective date: November 10, 2026. This notice describes TweetStreak version 1.0 with App Store purchases managed through RevenueCat.

TweetStreak is developed by Wesley Keetch. Privacy enquiries can be sent to [weskcode@duck.com](mailto:weskcode@duck.com).

## What the app stores

TweetStreak keeps activity records and settings on your device. These include post identifiers, timestamps and post types read from X; manual posts and replies counts; goal and rest-day history; time-zone and counting preferences; reminder settings; sync coverage and status; and milestone notification markers. Saved activity records do not contain post text or direct messages.

If you connect X, the app stores the public Client ID of your own X developer app, OAuth access and refresh credentials, and the verified account identifier and username in the iPhone's Keychain. Credentials use device-only Keychain protection. Activity files use iOS protection that makes them inaccessible after a reboot until the first unlock. The Home Screen widget reads a smaller local App Group summary without credentials.

TweetStreak does not operate an activity-storage server or include advertising. Activity files are not sent to a TweetStreak server. The app uses RevenueCat and RevenueCatUI for purchases, access validation, paywall presentation and subscription management. Apple, RevenueCat, X and GitHub process information when you use their services, as described below.

## The X connection

Connecting X is optional. You can enter counts manually or use the sample preview without signing in. Automatic tracking uses your own X developer app, which you create in X's Developer Console. X bills that developer account for API usage, separately from TweetStreak's App Store purchases. TweetStreak does not receive your payment-card details from Apple or X.

Sign-in uses X's OAuth flow. TweetStreak requests read access to posts and account identity, plus offline access for token refresh. It does not request permission to post, read direct messages or follow accounts. The app contacts X directly to sign in, refresh credentials and read activity. X receives those requests and processes information under the [X Privacy Policy](https://x.com/en/privacy) and its Developer Agreement and Policy.

Each sync rereads today and yesterday in your selected time zone. The first sync of each week also rereads from 13 days before that week began. These reads remove posts deleted on X from the local log. **Check all saved history** in Settings does the same for older saved posts, within X's limit of your most recent 3,200 posts.

Opening the linked X profile also opens X's service. X's own eligibility and privacy rules apply.

## Reminders and widgets

Reminders are local notifications scheduled on the device. TweetStreak does not operate a remote push-notification server. Reminder text can include remaining posts or replies based on your last saved progress. Depending on your iOS notification-preview settings, that text may appear on the Lock Screen.

Widget summaries contain saved progress and activity information. Widgets can make that information visible on your Home Screen. iOS controls notification delivery, background refresh and widget updates.

## App Store purchases and RevenueCat

The app offers monthly and yearly subscriptions and a one-time lifetime purchase through Apple. Apple handles the payment. RevenueCat processes purchase receipts or transaction information, product identifiers, purchase and subscription status, renewal and expiry information, and technical information to validate access and provide purchase management. Technical information includes the Apple vendor device identifier (IDFV), storefront country, locale, device model and operating-system version, app version and build number, app bundle identifier, preferred languages, installation source, and whether the app is in the background or a test environment. RevenueCat also receives the source IP address as part of the network connection. This purchase information also supports RevenueCat's dashboard analytics.

The app configures RevenueCat with an anonymous app user identifier and keeps that identifier, cached purchase status and queued interaction events on this iPhone. If you choose to contact support from the subscription-management screen, the message it prepares includes the RevenueCat user identifier, app version, device model, iOS version and App Store country. Sending the message shares those details, your message and your email address with the developer.

The app does not send your X account identifier, username, X credentials or posting history to RevenueCat, and does not set your name or email as RevenueCat customer attributes.

RevenueCatUI sends paywall and Customer Center interaction events to RevenueCat. These include impressions, purchase attempts, cancellations, error codes and messages, offering/package/product identifiers, component interaction values, locale, light or dark appearance, display mode and whether the session is in a test environment. Customer Center events can include the selected help path and predefined survey option. In this version, survey answers are option choices rather than free-text responses. The events include app user and session identifiers and timestamps, and support purchase-interface analytics. TweetStreak does not use these services for advertising across other companies' apps or websites.

If SDK diagnostic reporting is enabled with the developer's approval, RevenueCat can also receive request timings and network or StoreKit error details for troubleshooting.

RevenueCat processes this information on the developer's behalf. See [RevenueCat's privacy information](https://www.revenuecat.com/privacy) for its description of end-user data processing. Purchase-service information is separate from the local activity files. Clearing local app data, disconnecting X or uninstalling the app does not cancel an Apple subscription or automatically delete purchase records held by Apple or RevenueCat. Manage subscriptions through Apple or the app's subscription-management screen.

For requests about access to or deletion of purchase-service records, contact [weskcode@duck.com](mailto:weskcode@duck.com). A message sent from the subscription-management support screen includes the RevenueCat identifier used to locate the purchase-service record. We may also request relevant Apple purchase details to locate a record and may be unable to locate an anonymous record without suitable details. Do not send payment-card details, passwords or API keys. Records may need to be retained to meet legal obligations, resolve disputes or maintain purchase entitlements; this notice does not promise a fixed deletion deadline or automatic erasure by Apple.

## Apple and TestFlight

When you use the TestFlight beta, Apple collects beta usage and diagnostic information and makes reports and submitted feedback available to the developer. These may include your name or email, crash details, screenshots and information you provide. Do not put credentials or private activity in feedback. See [TestFlight and Privacy](https://www.apple.com/legal/privacy/data/en/test-flight/) and [Apple's TestFlight information](https://testflight.apple.com/).

Data held by Apple is subject to Apple's terms and retention rules. This is separate from TweetStreak's local activity files. The developer may use beta reports and feedback to investigate problems and improve the app.

## Support and public GitHub pages

The [support repository](https://github.com/weskcode/tweetstreak-support) and this notice are hosted by GitHub. GitHub processes visits and account activity under its [General Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

Support issues are public. Information you post can be seen by others. Share only what is needed to describe the problem, and do not post tokens, passwords, API keys, contact details or private activity. Send privacy questions privately to [weskcode@duck.com](mailto:weskcode@duck.com). GitHub manages information stored on its service under its own controls and retention rules.

## Retention, deletion and your choices

Saved activity remains on the device until you clear it or it becomes unavailable through device or app removal. Posts deleted on X are removed when their dates fall within a later sync recheck window, or when you run Check all saved history within X's newest-3,200-posts limit. Delete local app data removes them all.

- **Disconnect X** removes this device's saved X credentials and disables reminders. Cached activity stays visible. You can separately revoke the connection through X's connected-app settings.
- **Delete local app data** requires confirmation and clears the app's local activity, goals, preferences, widget summary, X Client ID and X credentials. It does not delete provider-held records on X, Apple, RevenueCat or GitHub, and does not cancel an App Store subscription. It also does not reset RevenueCat's on-device identifier, cached purchase status or queued interaction events. Those local purchase-service files normally remain until app removal; provider-held purchase records are separate.
- You can turn reminders off in the app or change notification permission and previews in iOS Settings.

TweetStreak does not provide its own cloud backup, export/restore tool or multi-device sync in this version. Activity files may be included in device backups, depending on iOS and your settings. Device-only X credentials do not transfer to a different device; reconnect X there. Normal app updates are intended to retain existing local records, but this is not a guarantee of recovery after deletion or device loss.

## Changes and contact

This public notice will be updated when the app's data handling changes. The effective date identifies the current notice. Send privacy questions and requests involving your purchase-service records to [weskcode@duck.com](mailto:weskcode@duck.com).
