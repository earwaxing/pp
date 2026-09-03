# Privacy Policy — Armani

**Last Updated:** September 3, 2026

This Privacy Policy applies exclusively to the Armani Discord bot and its operation within the idfk server. Armani is a private, closed-deployment bot and is not available to the public.

---

## 1. Overview

Armani is a private Discord bot developed for and operated solely within the idfk community. We are committed to handling all user data with transparency, care, and the minimum scope necessary for each feature to function. This document describes what data Armani collects, why it is collected, how long it is retained, and how you can exercise control over your data.

---

## 2. Data We Collect

Armani collects data only to support its active features. Below is a full breakdown by category.

### 2.1 Identifiers

The following Discord-issued identifiers are stored to associate data with the correct accounts, channels, and roles:

- **User IDs** — linked to economy balances, level progress, moderation history, birthdays, reminders, and other user-specific records.
- **Guild, Channel, and Role IDs** — used for server configuration, auto-role assignments, voicemaster setups, logging targets, and similar guild-scoped settings.

These are numeric identifiers issued by Discord and do not include display names, usernames, or email addresses directly — though username history may be recorded (see §2.4).

### 2.2 Activity & Engagement Statistics

Armani tracks engagement data to power leaderboards, leveling, and points systems:

- **Message counts** — tallied per user for leveling and weekly leaderboards. Message content is not retained for this purpose.
- **Voice connection duration** — tracked per session for voice activity leaderboards.
- **Command usage counts** — aggregate per-command statistics for top command tracking.
- **Bump counts** — recorded per user for the bump leaderboard.
- **Reaction history** — used for reaction-trigger functionality and reaction statistics.
- **Emoji usage** — tracked to power emoji usage leaderboards.
- **Mention counts** — logged per user for mention statistics.
- **Revive participation** — logged for the revive leaderboard.

### 2.3 Moderation & Safety Records

To maintain server safety and administrative accountability, Armani stores:

- **Warnings and punishment history** — records of issued warnings, mutes, jails, kicks, bans, and any other moderation actions taken against a user.
- **Moderation action logs** — timestamped history of actions performed by moderators.
- **Moderator notes** — staff-authored notes attached to user profiles, visible only to authorized moderators.
- **Alt account detection data** — metadata used to identify potential alternate accounts for anti-abuse purposes.
- **Anti-raid and anti-spam processing** — message content and join patterns are analyzed **in real-time and in-memory only**. This data is **never written to persistent storage**.
- **Recent joins** — a short-term record of recent member join events used for raid detection.
- **Jail list** — the current list of users in a jailed/restricted state.
- **Ban records** — recent ban history for moderation reference.

### 2.4 Social & Identity Records

- **Username / display name history** — Armani may log historical usernames to assist in moderation and identity verification.
- **Marriage records** — pairings created through the bot's social marriage feature, stored until dissolved by the users.
- **NDA acknowledgments** — records of users who have accepted a server Non-Disclosure Agreement through the NDA module.

### 2.5 User-Submitted Content

The following content is stored only because users explicitly create or submit it through bot commands:

- **Custom embeds** — saved embed templates created by users or staff.
- **Tags** — custom command tags authored by users or staff.
- **Diary entries** — personal diary entries written by users via the diary feature.
- **Birthdays and timezones** — voluntarily set by users for birthday announcements and timezone display.
- **Reminders** — scheduled reminder messages set by users.
- **Highlights** — keywords or phrases a user has configured to be notified about.
- **Suggestions** — content submitted through the suggestion system.
- **Ticket content** — messages and transcripts generated within support tickets, retained for staff reference.
- **Confessions** — submissions through the confession system. While confessions are displayed anonymously to the server, the submitting User ID is retained internally for moderation safety purposes only.

### 2.6 Economy & Reward Data

- **Economy balances** — virtual currency balances and transaction history.
- **Auto-tip records** — history of automated tips sent between users.
- **Giveaway participation** — records of entries and winners for server giveaways.
- **Color role assignments** — custom color roles linked to user accounts.
- **Temporary role records** — time-limited role assignments and their expiry data.

### 2.7 Server Configuration Data

Armani stores various server-level settings configured by administrators:

- Auto-role configurations, counter setups, logging channel targets, starboard settings, sticky message content, voicemaster templates, reaction trigger rules, webhook lists, disabled command lists, and similar per-guild configuration objects. This data does not contain personal user information.

---

## 3. Temporary & In-Memory Data

### 3.1 Snipe Cache

Deleted messages and edited message content are temporarily stored in a **volatile in-memory cache** to power the snipe feature. This cache is **automatically purged after 2 hours** and is never written to the persistent database.

### 3.2 Real-Time Processing (No Retention)

The following data is processed entirely in-memory and is **never persisted**:

- Message content analyzed by the anti-spam module for flood/duplicate detection.
- Join metadata analyzed by the anti-raid module for pattern detection.
- Audio streams processed through the music module.

---

## 4. External Service Lookups

Armani integrates with a number of external platforms to fulfill on-demand user requests (e.g., looking up a Roblox profile, fetching song lyrics, retrieving a TikTok video). These include:

> Roblox · TikTok · Instagram · Snapchat · Twitter/X · YouTube · Pinterest · Spotify · IGDB · TMDB · AO3 · Wattpad · Goodreads · Google · CashApp · Shazam

**Armani does not store the results of these lookups.** Data is fetched, returned to the user, and discarded. Armani does not cache, log, or share any personally identifiable information returned by these third-party services. Users should consult the respective platform's own privacy policy regarding how those services handle requests.

---

## 5. How We Use Your Data

All data collected by Armani is used **exclusively** to operate its features within idfk. Specifically:

- User and guild identifiers are used to route data to the correct records.
- Activity statistics are used solely to calculate rankings, levels, and leaderboard positions.
- Moderation records exist to support staff accountability, consistent enforcement, and appeals.
- User-submitted content is stored to fulfill the feature the user explicitly opted into.

**We do not sell, rent, license, or share any user data with third parties, advertisers, or external developers.**

---

## 6. Data Retention & Deletion

### 6.1 Standard Retention

Data associated with a user persists within Armani's database for as long as it is relevant to an active feature — for example, economy balances, level progress, and moderation history are retained indefinitely unless reset by an administrator or deleted upon request.

Server configuration data is retained until Armani is removed from the server or an administrator clears it.

### 6.2 Self-Service Deletion

Users can delete certain categories of their own data directly through bot commands, including but not limited to:

- **Diary entries** — via the diary management commands
- **Reminders** — via the reminders management commands
- **Highlights** — via the highlights management commands
- **Birthday / Timezone** — via the respective clear commands
- **Economy participation** — subject to server administrator settings

### 6.3 Manual Deletion Requests

Users may request the immediate and permanent deletion of all personally identifiable data associated with their Discord account by joining the support server at **https://discord.gg/idfk** and contacting the development team. Requests will be processed in a timely manner.

Note: Some moderation records (e.g., bans, punishment logs) may be retained by server administrators independently of Armani's database for legal or community safety reasons, even following a data deletion request.

---

## 7. Data Security

Armani's database is self-hosted and access is restricted to the bot's development team. Redis caches used for temporary data are volatile and automatically expire. No sensitive authentication credentials or personal contact information (email addresses, phone numbers, etc.) are ever collected or stored by Armani.

---

## 8. Children's Privacy

Armani does not knowingly collect data from individuals under the age of 13, consistent with Discord's own Terms of Service. If you believe a minor's data has been collected, please contact the development team via the support server.

---

## 9. Changes to This Policy

This Privacy Policy may be updated periodically to reflect changes to Armani's feature set or operational practices. The "Last Updated" date at the top of this document will always reflect the most recent revision. Continued use of Armani following any changes constitutes acceptance of the updated policy.

---

## 10. Contact

For privacy-related inquiries, data deletion requests, or any questions regarding this policy, please reach out through the idfk support server:

**Support Server:** https://discord.gg/idfk

---

*Armani is a private bot operated for the idfk community. This policy governs data handling within that context only.*
