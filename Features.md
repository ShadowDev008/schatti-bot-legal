# Schatti Bot
A multifunctional Discord bot with moderation, automod, utility, fun, ticket, and logging systems.
## Bot Information
- **Version:** `1.0`
- **Primary Language:** `German`
- **Support Server:** `https://discord.gg/czGP5NHQGA`
---
# Features
## Moderation
- `/kick` — Kicks a user with a reason and logs the action
- `/ban` — Permanently bans a user
- `/unban` — Unbans a user by ID
- `/mute` — Applies a timed timeout (e.g. 10m, 1h, 2d)
- `/unmute` — Removes a timeout
- `/warn` — Gives a user a warning
- `/unwarn` — Removes a warning
- `/warns` — Shows all warnings of a user
- `/clear` — Deletes a specified number of messages
- `/lock` / `/unlock` — Locks or unlocks a channel
- `/role` — Gives or removes a role from a user
- `/setlog` — Sets the log channel for automatic logging
---
## Automatic Logging
Automatically logs:
- Deleted & edited messages
- Ghost pings
- Voice activities (join/leave/switch)
- Nickname changes
- Role changes
- Channel creations/deletions
- Bans/unbans
- Used commands
- Member joins & leaves
---
## Word Blacklist
- `/word_blacklist` — Adds a banned word with a selectable punishment
- `/word_blacklist_remove` — Removes a word from the blacklist
- `/word_blacklist_list` — Shows all blacklisted words
---
## Automod
### Filters
- Anti-Spam
- Anti-Link
- Anti-Invite
- Anti-Caps
- Anti-Mention-Spam
- Anti-Emoji-Spam
- Anti-Duplicate
### Features
- Configurable punishments
- Role whitelist
- Channel whitelist
- Managed with `/automod enable/disable`
---
## Ticket System
- `/setup_ticket` — Creates a full ticket system
Features:
- Button-based ticket creation
- Automatic transcript saving
- Log channel support
---
## Welcome & Goodbye
- `/setup_welcome` — Sets custom welcome/goodbye messages
- `/welcome_disable` — Disables the system
Supports placeholders:
- `{user}`
- `{server}`
- `{count}`
---
## Auto-Role
- `/setup_autorole` — Automatically assigns a role to new members
- `/autorole_disable` — Disables auto-role
---
## Giveaways
Features:
- Create giveaways
- Manage giveaways
- Automatic winner selection
---
## Reaction Roles
Users can assign themselves roles through reactions.
---
## Utility
- `/timer`
- `/reminder`
- `/afk`
- `/embed`
- `/userinfo`
- `/serverinfo`
- `/avatar`
- `/ping`
- `/botinfo`
---
## Fun & Games
- `/8ball`
- `/tictactoe`
- `/poll`
- `/ship`
- `/hack`
- `/ragebait`
- `/quiz`
- `/hangman`
- `/zahlenraten`
