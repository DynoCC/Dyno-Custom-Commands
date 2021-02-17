# Utility Commands
Commands designed by the Strand Team.
> Useful commands for communication and general server improvement.

## Guide Markdown  
We assume you are using the default command prefix, `?`. Commands with inputs are denoted as ``?command [input]``. Commands with choice inputs are denoted as ``?command [input1/input2]``. Commands with optional inputs are denoted as ``?command (input)``.

## Commands
* `?dm [user] [message]` - Sends a dm to the speficied user and then posts the message if successful.
* `?link [link] [message]` - Creates an embed containing a link, along with a message.
* `?lookup [user]` - Shows information about the specified user (Updated by TheSilentPro#9920).
* `?mention [user] [message]` - Mentions the user, shows their status and then says the message you provide. 
* `?owner [message]` - Sends a message to the server owner via DMs.
* `?panel (module)` -  Links to the server's dashboard.
* `?reddit [subreddit]` - Searches the provided subreddit and then outputs the result in an embedded message. 
* `?status [user]` - Checks the status of the specified user.  
* `?superclean` -  Removes all Dyno command triggers and responses from the channel.
* `?channelinfo [channel/category]` - Displays information about a channel or category (including voice channel).
* `?screenshare [voice channel]` - Gets the screenshare link for a voice channel. 
* `?erole [role]` - Adds or deletes a role, depending on whether or not it already exists.
* `?spotify [...song]` - Provides a Spotify App Protocol URL to open Spotify with a search.
* `?reset (song)` - Has Dyno leave and join the queue. If a song is specified, Dyno will clear the queue and play it.
* `?copy [role]` - Copies a specified role. The user must have Server Administrator.
* `?roleswap [role 1] [role 2]` - Swaps the members of the specified roles. You must use this command four times for a full swap. The user must have Server Administrator. 
* `?rolemention [channel] [role] [message...]` - Enables mentionablity for a role, sends a message to the specified channel mentioning the role, then disables the mentionability. The user must have Server Administrator.

Currently Bugged:
* `?pomodoro` - Sets a [Pomodoro Timer](https://francescocirillo.com/pages/pomodoro-technique) for the user.

### Note
The `?remindme` command is currently bugged, which may affect the `?pomodoro` command.