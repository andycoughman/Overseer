# Privacy Policy

**Bot:** Overseer ("the Bot", "we", "us")
**Operator:** @billybigb (Discord)
**Contact:** https://discord.gg/caM3E6mFZx
**Last updated:** October 3, 2026

Overseer is a Discord moderation bot that protects servers from "nuking" (mass bans, mass channel or role deletion, and similar destructive actions) and restores server structure when damage occurs. This policy explains what information the Bot processes and why.

## 1. Summary

- The Bot does **not** collect, store, or sell personal user data.
- The Bot does **not** read, log, or store message content, direct messages, attachments, or voice data.
- The Bot stores **server (guild) configuration data** needed to restore a server after an attack.
- Some Discord IDs (such as a user ID) are processed briefly to detect and stop an attack. They are not used to build user profiles.

## 2. Information We Process

### 2.1 Server (guild) data we store
To restore a server after an attack, the Bot keeps a snapshot of the server's structure, which may include:

- Server ID, and the IDs and names of channels, categories, and roles
- Channel types, topics, positions, slowmode and similar settings
- Role names, colours, positions, and permission settings
- Channel and category permission overwrites (these reference role IDs and may reference user IDs)
- Bot configuration for that server (for example, a whitelist of trusted user or role IDs and the thresholds chosen by server admins)

### 2.2 Event data we process but do not keep
To detect attacks, the Bot receives real-time events from Discord (for example, a channel being deleted or a member being banned) and may read the server audit log. These events include the ID of the user who performed the action and the ID of the target. This data is used in memory to decide whether to take protective action (such as removing roles from or banning the offender) and is **not stored** beyond a short in-memory window.

### 2.3 What we do not collect
We do not collect or store: message content, direct messages, email addresses, IP addresses, usernames or avatars for profiling, payment information, or any data from outside Discord.

## 3. How We Use Information

We use the information above only to:

1. Detect and respond to destructive actions in a server
2. Restore deleted channels, categories, and roles
3. Apply the settings chosen by the server's administrators
4. Maintain, secure, and debug the Bot

We do not use data for advertising, profiling, or training machine learning models, and we do not sell or rent data.

## 4. Sharing

We do not share, sell, or disclose data to third parties, except where required by law or to protect against abuse or security threats. Data is processed on infrastructure operated by a third-party hosting provider, which acts solely as our hosting provider.

## 5. Retention and Deletion

- Server snapshots are kept while the Bot is in the server.
- When the Bot is removed from a server, the stored data for that server is deleted within 30 days.
- A server owner or administrator can request earlier deletion of their server's data by contacting us at andrewcoughman69@gmail.com. If you believe the Bot holds data about you personally, contact us and we will delete it on request.

## 6. Security

Data is stored on access-controlled servers, and access is limited to the Bot's operators. No system is perfectly secure, but we take reasonable measures to protect stored data.

## 7. Children

The Bot is intended for use on Discord, which requires users to meet its minimum age. We do not knowingly collect personal data from children.

## 8. Discord

Use of the Bot is also subject to Discord's [Terms of Service](https://discord.com/terms) and [Privacy Policy](https://discord.com/privacy). The Bot operates in accordance with Discord's Developer Terms of Service and Developer Policy.

## 9. Changes

We may update this policy from time to time. The "Last updated" date above shows the latest revision. Continued use of the Bot after changes means you accept the updated policy.

## 10. Contact

Questions or deletion requests: https://discord.gg/caM3E6mFZx.
