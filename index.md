---
title: Clutch Cricket Privacy Policy
---

# Clutch Cricket Privacy Policy

Effective date: September 12, 2026

This policy describes the Android release of **Clutch Cricket**, also listed as **Clutch Cricket: Hand Cricket**, published by **fawkesthephoenix**. Its Android package is `com.gullyxi.handcricket`. “We” means the game's publisher.

## The short version

You can play without entering a name, email address or other public profile information. The game creates a random Unity player identifier to back up a limited career summary and check ranking availability. A player must deliberately secure that guest profile with Unity Player Accounts before making a purchase, so paid items can be recovered on another device. **Unity Analytics is off unless you enable it in Settings. Rewarded advertising is paused in this release and its SDK is not initialized.** The game has optional Google Play purchases; it has no active advertisements, online multiplayer, chat or precise-location access.

## Information stored on your device

The game stores career progress, scores, story and challenge progress, Try Ball and Gem balances, unlocks, squad choices, country or region flag preference, interrupted-match checkpoints, sound and vibration choices, Analytics choice, the selected age band, and bounded diagnostic event logs. A flag is cosmetic, not a determination of nationality or location. Local diagnostic logs rotate by size and are not uploaded to us.

The game does not request your name, phone number, contacts, precise location, photos, microphone recordings or advertising identifier to play.

## Online progress, accounts and rankings

Unity Authentication creates a random player identifier. Unity Cloud Save receives a limited career summary containing aggregate match results, highest scores, story completion, experience and cosmetic unlock identifiers. Try Balls, raw purchase receipts, daily-grant records and unfinished hidden hand selections are excluded from that ordinary career summary.

The optional **Secure Account** action opens Unity Player Accounts sign-in and links the current guest profile, allowing the same Unity Authentication player and its cloud entitlements to be restored on another supported device. Unity operates that sign-in page and the account credentials; the game does not receive the player's Unity Account password.

The game can read public ranking availability through Unity Leaderboards. It does not submit scores in this release. Matches still work and save locally when online services are unavailable. Guest progress is not recoverable after reinstall unless it was secured first.

Unity processes online-service data under its [game player privacy information](https://unity.com/legal/game-player-and-app-user-privacy-policy). Network traffic to these services is encrypted in transit.

## Optional analytics

If you opt in under Settings, Unity Analytics receives only three developer-defined event names: match mode selected, match started and match completed. Those events contain no developer-defined parameters. We do not put names, email addresses, scores, country or flag choice, free-form text or local match identifiers in them.

Unity Analytics may also process service data such as IP address, approximate location inferred from IP, an installation-specific identifier, session information, platform or device information and app lifecycle events. Analytics is not required to play. You can turn it off at any time; the game then denies Analytics consent and requests deletion of Analytics data associated with that installation.

## Purchases and protected economy ledger

Optional purchases are processed by Google Play Billing. Offers include 100 or 300 Gems, a permanent Story Pass, and a Founder Pack. Google processes payment credentials; the game does not receive or store payment-card numbers.

Our Unity Cloud Code purchase module receives the Unity player identifier, product identifier and Google Play purchase token needed to validate an order with the Google Play Developer API. Google Play receives a one-way hash of the player identifier during checkout, and the module requires the matching hash before granting an item. A protected Unity Cloud Save ledger stores cumulative purchased and spent Gems, Story Pass and Founder Pack ownership, premium story and sign unlock identifiers, and a bounded list of hashed transaction identifiers. Paid delivery and premium Gem spending are accepted only after the server verifies and records the operation using conflict-safe write locks. Verified purchases are acknowledged or consumed through Google Play's server API. This prevents duplicate delivery, replay and overspending.

Purchases require Secure Account sign-in. Gems can unlock eligible story moments and signs. Try Balls are not sold and are used only for Story retries. In-game items are not cash and cannot be transferred outside the game.

## Rewarded advertising

Rewarded-video code and the Unity LevelPlay package are included, but advertising is fail-closed in this release: ad service keys are blank, signed server-to-server reward verification is not enabled, the SDK is not initialized, and the Android advertising-ID permission is removed during manifest merging. The age-band screen also prevents ad initialization for players under 18. No ad can currently be requested or shown.

If rewarded videos are enabled in a future update, this policy and the Play Data Safety answers will be updated first, signed server-side reward verification will be required, and adult players will retain an explicit opt-in. Free Quick Match play will not require advertising.

## Permissions

The game uses Android vibration for optional haptic feedback and network access for online progress, secure sign-in, purchase validation and optional Analytics. This release removes Android advertising-ID access. It does not request camera, microphone, contacts or device-location permissions. Audio plays from bundled assets; the game does not record your voice.

## Retention, controls and deletion

Local records remain until overwritten, cleared in Android settings or removed with the app, subject to device backup settings. Local diagnostic logs keep a current file and one previous file, each limited to 512 KiB.

To request deletion of the game profile, cloud career summary and protected purchase ledger, open **Settings → Data & Help → Delete Online Data** and confirm the second prompt. Keep the game open and connected until completion appears. Successful deletion disables future online syncing on that installation. Your local save remains, but paid entitlements tied to the deleted profile can become unrecoverable. A linked Unity Player Account is separate and operated by Unity; use **Manage Account** in the game to open Unity's account portal for its controls. Some transaction and fraud-prevention records may need to be retained for refunds, security or legal obligations.

To remove local data, use Android Settings → Apps → Clutch Cricket → Storage → Clear storage. Turning Analytics off sends Unity Analytics a deletion request for data associated with that installation; keep the game installed and connected long enough for it to complete.

## Children and families

The Play release is intended for players aged 13 and older and is not directed to children under 13. On first launch, the game asks only for one of three age bands (13–15, 16–17, or 18+) to apply privacy and advertising safeguards; it does not ask for a birth date. Advertising is unavailable to players under 18 and paused for everyone in this release. The game has no public profiles or chat. Parents and guardians can use Google Play purchase controls and the deletion controls above.

## Google Play, device services and this website

Google Play, Android, device manufacturers or backup providers may independently process installation, payment, device, diagnostic and backup information under their own settings and policies. Eligible crash, unresponsive-app and performance reports may be available through Android vitals. The game contains no enabled remote crash-reporting SDK.

This page is hosted on GitHub Pages without added analytics, advertising, tracking pixels or forms. GitHub processes website requests under the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## Contact and changes

Email privacy inquiries to **fawkesthepheonix240@gmail.com**. You may also [open a public GitHub inquiry](https://github.com/asim1342/clutch-cricket-public/issues/new?title=Privacy%20inquiry); do not post personal information, private logs, passwords or confidential details in a public issue.

We will update this page and its effective date when the game's data practices change. Score submission, multiplayer or active advertising will require updated disclosures before they are enabled.
