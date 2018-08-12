# **Extensive Mod Commands**

## Requirements
- A role named "Muted".

## Information and Usage
1. `?mute-kick` - Mutes the specified user forever and then kicks the user. 
- Usage: `?mute-kick [user] [reason]`
- Example: `?mute-kick @Nex#4568 Spam.`

2. `?mute-ban` - Mutes the specified user forever and then bans the user.
- Usage: `?mute-ban [user] [reason]`
- Example: `?mute-ban @Nex#4568 Spam.`

3. `?mute-tban` - Mutes the specified user forever and then bans the user for the specified time.
- Usage: `?mute-tban [user] [ban-limit] [reason]`
- Example: `?mute-tban @Nex#4568 1d Spam.`

4. `?mute-sban` - Mutes the specified user forever and then softbans the user.
- Usage: `?mute-sban [user] [reason]`
- Example: `?mute-sabn @Nex#4568 Spam.`

5. `?pc-ignore` - Purges the specified user's and dyno's last specified messages and then ignores the user.
- Usage: `?pc-ignore [user] [purge&clean-number] [reason]`
- Example:`pc-ignore @Nex#4568 6 Spamming bot commands in #general.`

6. `?badnick` - Changes the nickname of the specified user to "Nice Nickname".
- Usage: `?badnick [user]`
- Example: `?badnick @Nex#4568`

#### FAQ

Q.1 - Who can use thse commands?
- Anyone who shows under the "Moderators" section of `?listmods`.

Q.2 - How can I add a `serverMod`?
- You can add a `serverMod` using the `?addmod` command.
