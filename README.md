# TweetStreak Privacy Notice

Effective date: November 1, 2026. This notice describes TweetStreak version 1.0.

## What the app stores

TweetStreak keeps activity records and settings on your device. These include post identifiers, timestamps and post types read from X; manual posts and replies counts; goal and rest-day history; time-zone and counting preferences; reminder settings; sync coverage and status; and milestone notification markers. Saved activity records do not contain post text or direct messages.

If you connect X, the app stores the public Client ID of your own X developer app, OAuth access and refresh credentials, and the verified account identifier and username in the iPhone's Keychain. Credentials use device-only Keychain protection. Activity files use iOS protection that makes them inaccessible after a reboot until the first unlock. The Home Screen widget reads a smaller local App Group summary without credentials.

TweetStreak does not operate an app backend or include an advertising or analytics SDK. Activity files are not sent to a TweetStreak server. Apple, X and GitHub process information when you use their services, as described below.

## The X connection

Connecting X is optional. You can enter counts manually or use the sample preview without signing in. Automatic tracking uses your own X developer app, which you create in X's Developer Console. X bills that developer account for API usage; TweetStreak takes no payment and never sees your payment details.

Sign-in uses X's OAuth flow. TweetStreak requests read access to posts and account identity, plus offline access for token refresh. It does not request permission to post, read direct messages or follow accounts. The app contacts X directly to sign in, refresh credentials and read activity. X receives those requests and processes information under the [X Privacy Policy](https://x.com/en/privacy) and its Developer Agreement and Policy.

Each sync rereads your posts from the last 7 days and removes any you deleted on X from the local log. **Check all saved history** in Settings does the same for older saved posts, within X's limit of your most recent 3,200 posts.

Opening the linked X profile also opens X's service. X's own eligibility and privacy rules apply.

## Reminders and widgets

Reminders are local notifications scheduled on the device. TweetStreak does not operate a remote push-notification server. Reminder text can include remaining posts or replies based on your last saved progress. Depending on your iOS notification-preview settings, that text may appear on the Lock Screen.

Widget summaries contain saved progress and activity information. Widgets can make that information visible on your Home Screen. iOS controls notification delivery, background refresh and widget updates.

## Apple and TestFlight

When you use the TestFlight beta, Apple collects beta usage and diagnostic information and makes reports and submitted feedback available to the developer. These may include your name or email, crash details, screenshots and information you provide. Do not put credentials or private activity in feedback. See [TestFlight and Privacy](https://www.apple.com/legal/privacy/data/en/test-flight/) and [Apple's TestFlight information](https://testflight.apple.com/).

Data held by Apple is subject to Apple's terms and retention rules. This is separate from TweetStreak's local activity files. The developer may use beta reports and feedback to investigate problems and improve the app.

## Support and public GitHub pages

The [support repository](https://github.com/weskcode/tweetstreak-support) and this notice are hosted by GitHub. GitHub processes visits and account activity under its [General Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

Support issues are public. Information you post can be seen by others. Share only what is needed to describe the problem, and do not post tokens, passwords, API keys, contact details or private activity. To ask a privacy question, open a general support request without personal information. GitHub manages information stored on its service under its own controls and retention rules.

## Retention, deletion and your choices

Saved activity remains on the device until you clear it or it becomes unavailable through device or app removal. Posts deleted on X are removed from the local activity log at the next sync if they are from the last 7 days, or when you run Check all saved history. Delete local app data removes them all.

- **Disconnect X** removes this device's saved X credentials and disables reminders. Cached activity stays visible. You can separately revoke the connection through X's connected-app settings.
- **Delete local app data** requires confirmation and clears the app's local activity, goals, preferences, widget summary, X Client ID and X credentials. It does not delete anything on X, Apple or GitHub.
- You can turn reminders off in the app or change notification permission and previews in iOS Settings.

TweetStreak does not provide its own cloud backup, export/restore tool or multi-device sync in this version. Activity files may be included in device backups, depending on iOS and your settings. Device-only X credentials do not transfer to a different device; reconnect X there. Normal app updates are intended to retain existing local records, but this is not a guarantee of recovery after deletion or device loss.

## Changes and contact

This public notice will be updated when the app's data handling changes. The effective date identifies the current notice. Privacy questions can be raised through the [support repository](https://github.com/weskcode/tweetstreak-support/issues/new) without including personal information.
