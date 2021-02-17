# Moderation Commands
Commands designed by the Strand Team.  

> Got a server going wild? Then these commands are for you! These commands help to efficiently moderate a server with ease.

## Guide Markdown
We assume you are using the default command prefix, `?`. Commands with inputs are denoted as ``?command [input]``. Commands with choice inputs are denoted as ``?command [input1/input2]``. Commands with optional inputs are denoted as ``?command (input)``.


## Commands
* `?badnick [user]` - Changes the nickname of the specified user to "Something Suitable" and notifies them.
* `?cooldown [user]` - Mutes the specified user for 2 minutes and purges their last 5 messages.
* `?spam [user] [message number]` - Warns the specified user and purges a specified amount of messages. Use for clearing spam.
* `?mute-ban [user] (reason)` - Mutes and bans the specified user.
* `?mute-kick [user] (reason)` - Mutes and kicks the specified user.
* `?mute-sban [user] (reason)` - Mutes and softbans the specified user.
* `?mute-tban [user] [limit] (reason)` - Mutes and temp-bans the specified user.
* `?pc-ignore [user] [message number] (reason)` - Cleans all Dyno command trigger and responses as well adds the specified user to the ignored list. 
* `?pingmods [message]` - Pings the moderators with a message. Requires two roles: `Trusted` & `Moderator` and one channel: `#mod-pings`. Users must have Trusted.
* `?lc [channel] [message...]` - Locks the specified channel, or unlocks it if it is already locked. Users must have Server Administrator.