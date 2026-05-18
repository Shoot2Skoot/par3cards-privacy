# Par 3 Cards — Privacy Policy

_Last updated: 2026-05-17_

This Privacy Policy describes how Par 3 Cards ("we", "the app") collects, uses,
and shares information about you when you use our mobile application.

## Summary

- We do not require an email address, phone number, or any third-party login.
- We collect the bare minimum needed to run the game: a randomly-generated
  anonymous account identifier and a display name you choose.
- We do not sell your data. We do not share your data with advertisers beyond
  the limited information required to serve ads (when ads are present in the
  app — see the **Advertising** section).
- You can delete all of your data at any time from inside the app.

## Information We Collect

**Anonymous account identifier.** When you first open Par 3 Cards we create an
anonymous account in our authentication system (Supabase). This account has no
email, name, phone number, or other identifying information attached to it —
just a random UUID. The identifier is stored locally on your device so the
same anonymous account is reused across sessions on that device.

**Display name.** You choose a display name when joining or hosting a
multiplayer room. This name is shared with other players in the same room so
they can tell players apart. It is stored against your anonymous account.

**Game state.** When you play a multiplayer game, the state of the game (which
cards have been played, scores, whose turn it is) is stored on our server so
that all players in the same game see a consistent view, and so you can
rejoin a game if you briefly lose connection. Game state is associated with
the room you are playing in, not with you individually beyond your seat in
that room.

**Connection metadata.** When you are connected to a multiplayer game we
record presence information (you are currently in the room) and the
timestamp of when you last lost connection. This is used to allow other
players' turns to proceed if you disconnect for an extended period.

**Crash and diagnostic information.** If the app crashes, anonymized crash
reports (call stack, OS version, device model) may be sent to our error
monitoring provider (Sentry) so we can diagnose and fix bugs. These reports
do not include your account identifier, display name, or game state.

## Information We Do Not Collect

We do not collect:

- Your real name, email address, phone number, or postal address.
- Your contacts, photos, microphone, camera, location, or any other device
  sensors.
- Your purchase history outside Par 3 Cards.
- Tracking identifiers across other apps or websites.

## How We Use Information

We use the information we collect to:

- Run multiplayer games (synchronizing state across the players in a room).
- Allow you to rejoin a game in progress after a brief disconnect.
- Diagnose and fix bugs (via anonymized crash reports).
- Serve advertising (see **Advertising** below).

## Advertising

Par 3 Cards displays advertisements served by Google AdMob. AdMob may use
device-level identifiers (such as the Apple Advertising Identifier, IDFA) to
serve ads. The first time the app launches we will ask, via Apple's App
Tracking Transparency prompt, whether you would like to allow this. You can
change your choice at any time in iOS Settings → Privacy & Security →
Tracking.

For information about how Google handles ad data, see Google's privacy
policy: <https://policies.google.com/privacy>.

We do not share your account identifier, display name, or game state with
advertisers.

## Data Retention

- **Account data** (your anonymous identifier and display name) is retained
  for as long as your account exists. You can delete your account from
  inside the app at any time (Settings → Delete my data).
- **Game state** is retained for as long as the game is in progress and for
  a short period afterwards (typically less than 24 hours) so that recent
  scores can be reviewed. Finished games are deleted on a rolling basis.
- **Empty lobbies** (rooms that were created but never started) are deleted
  automatically after a short period of inactivity.
- **Crash reports** are retained by our error monitoring provider per their
  policy (typically 90 days).

## Deleting Your Data

To delete all of your data:

1. Open the app.
2. Tap the **Settings** gear icon.
3. Tap **Delete my data**.
4. Confirm.

This removes your account identifier, your display name, your membership in
any rooms you joined, and any rooms you hosted (which will end any
in-progress games in those rooms for the other players). The deletion is
immediate and cannot be undone.

If you uninstall the app without deleting your data first, the local copy of
your anonymous identifier is removed from your device but the server-side
record remains. Reinstalling will create a fresh anonymous account.

## Children

Par 3 Cards is not directed to children under 13 and we do not knowingly
collect data from children under 13. The app does not provide any
mechanism for children to provide personal information beyond a
self-chosen display name.

## Third-Party Services

The following third parties receive data when you use Par 3 Cards:

- **Supabase** (database, authentication, realtime infrastructure) —
  receives your anonymous account identifier, display name, and game state.
  See <https://supabase.com/privacy>.
- **Google AdMob** (advertising) — may receive device-level ad identifiers
  per Apple's App Tracking Transparency choice you make. See
  <https://policies.google.com/privacy>.
- **Sentry** (crash reporting) — receives anonymized crash reports. See
  <https://sentry.io/privacy/>.

## Changes to This Policy

If we change this policy in a meaningful way we will update the "Last
updated" date at the top and surface a notice in the app on next launch.

## Contact

For questions about this Privacy Policy or your data, contact us at
**pendzich.cody@gmail.com**.
