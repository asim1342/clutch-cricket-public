---
title: Clutch Cricket Privacy Policy
---

# Clutch Cricket Privacy Policy

Effective date: September 11, 2026

This policy describes the Android release of **Clutch Cricket**, also listed as **Clutch Cricket: Hand Cricket**, published by **fawkesthephoenix**. Its Android package is `com.gullyxi.handcricket`. “We” means the game's publisher.

## The short version

You can play without entering a name, email address or other profile information. The game creates a random Unity player identifier so it can back up a limited career summary and check public ranking availability. Detailed gameplay records and paid-economy data stay on your device. **Unity Analytics is off unless you choose to enable it in Settings.** The release does not include advertising, active in-app purchases, online multiplayer, chat or precise-location access.

## Information stored on your device

The game uses local storage to keep:

- Career progress, scores, match results, story/challenge progress, Try Ball and Gem balances, unlocks, squad choices and country or region flag preferences.
- Premium-story ownership and purchase-replay records reserved for a future commerce release. Purchases are disabled in this release.
- An interrupted match's saved state, where a checkpoint is available, so you can resume playing.
- Sound, vibration and analytics choices.
- Bounded local gameplay event logs used for diagnostics. These detailed logs are not uploaded to us.

A flag is a cosmetic choice, not a determination of physical location or nationality. The game does not request your name, email, phone number, contacts, precise location, photos, microphone recordings or advertising identifier to play.

## Online progress and rankings

Unity Authentication creates a random player identifier without asking for personal profile information. Unity Cloud Save receives a limited career-recovery summary containing aggregate match results, highest scores, story completion, experience and cosmetic unlock identifiers. Try Balls, Gems, premium-story ownership, purchase receipts, transaction identifiers, daily-grant records and unfinished hidden hand selections are excluded from that cloud summary.

The game reads public ranking availability through Unity Leaderboards. It does not submit player scores in this release. Matches still work and save locally when online services are unavailable. Anonymous progress cannot currently be recovered after reinstall or on another device because no platform-account linking flow is included.

Unity processes the random player identifier and cloud summary as the service provider operating Authentication, Cloud Save and Leaderboards. Network traffic to these services is encrypted in transit. See [Unity's game player privacy information](https://unity.com/legal/game-player-and-app-user-privacy-policy).

## Optional analytics

If you opt in under Settings, Unity Analytics receives only three developer-defined event names: match mode selected, match started and match completed. Those events contain no developer-defined parameters. We use their counts to understand the path from mode choice to match completion. We do not put names, email addresses, scores, country/flag choice, free-form text or local match identifiers in these events.

Unity Analytics also processes service data such as IP address, approximate location inferred from IP, an installation-specific identifier, session information, platform/device information and app lifecycle events. Analytics is not required to play and remains off until you enable it. You can turn it off at any time. Unity states that Analytics data is encrypted in transit. We do not sell analytics information or share it with advertisers.

## Permissions, advertising and purchases

The game uses Android's vibration permission for optional haptic feedback and network access for online progress, ranking availability and optional Analytics. It does not request camera, microphone, contacts or device-location permissions. Sound effects, music and number calls play from bundled assets; the game does not record your voice.

Future rewarded-ad and Gem-pack offers are visibly disabled in this release. No advertising SDK, advertising identifier access, active billing system or real-money purchase flow is included. This policy and the Google Play disclosures will be updated before advertising or purchases are enabled.

## Retention, controls and deletion

Local records remain until overwritten, cleared in Android settings or removed with the app, subject to your device's backup settings. Local diagnostic logs rotate by size: the current log and one previous log are each limited to 512 KiB.

To delete the random Unity account and its cloud career summary, open **Settings → Data & Help → Delete Online Data** and confirm the second prompt. Keep the game open and connected until completion appears. Successful deletion also disables future online syncing on that installation. Your local save remains on the device. Because this release never submits leaderboard scores, there is no player leaderboard entry to delete.

To remove local data, use Android Settings → Apps → Clutch Cricket → Storage → Clear storage (wording varies by device). Turning Analytics off stops Analytics collection and sends Unity Analytics a deletion request for data associated with that installation. Keep the game installed and connected long enough for that request to complete.

## Google Play, device services and this website

Google Play, Android, your device manufacturer or backup provider may independently process installation, device, diagnostic and backup information under their own settings and policies. Eligible crash, unresponsive-app and performance reports may be available to us through Android vitals. The game contains no enabled remote crash-reporting SDK.

This policy is hosted on GitHub Pages without added analytics scripts, advertisements, tracking pixels or forms. GitHub processes website requests under the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Visiting this page does not upload game progress or local gameplay logs.

## Privacy inquiries

You can [submit a privacy inquiry to the publisher](https://github.com/asim1342/clutch-cricket-public/issues/new?title=Privacy%20inquiry). This creates a **public GitHub issue**, requires a GitHub account and displays the username and message you choose to submit. Do not post personal information, private logs, passwords or confidential details. We use information you deliberately submit only to answer the request or investigate the issue, not for marketing.

## Children and families

The game does not ask players to provide profile information, use chat, view targeted advertising or make purchases in this release. Parents and guardians can use the deletion controls above. If you believe a child submitted personal information through the public support channel, request removal without reposting that information.

## Changes

We will update this page and its effective date when the game's data practices change. Ads, purchases, score submission, account linking or multiplayer will require updated disclosures before they are enabled.
