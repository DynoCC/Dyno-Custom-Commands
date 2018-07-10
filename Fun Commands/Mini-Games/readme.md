# Mini-Games

We assume you are using the `?` prefix for this guide. We will denote inputs as `[input]` and choice inputs as `[input1/input2]` respectively.

*If you have any problems with the commands, you can visit the [Dyno Custom Commands Server](https://discord.gg/D3K3Fqz)'s Support Channel for help.*

## Caesar Mini-Game
Command by Amosharper

> A simple game where only one person can hold the role of ``Caesar``, and anyone can claim it. Requires an existing role of ``Caesar``, preferably with a distinct color. Could give ``Caesar`` special privileges, like the ability to post embeds, or use external emoji, or to mute other users. Since the calling message is deleted (to cut down on bot spam), you'll need to document the command somewhere.

### Requirements
 - Create the role ``Caesar``. If you'd like, you can give it specific permissions, as per the description above.
 - (Optional) Add requirements to the command forcing it to be used in a specific channel. For example, to force the command to be used only in the channel, ``#throne-room``, place in the command ``{require:#throne-room}``.

### Usage
 - The syntax for this command is ``?crownme``.
 - A member who does not currently hold the role of ``Caesar`` can use the command, which moves them to the role of Caesar.
 - When this command is run, it removes the ``Caesar`` role from any other users.

## Infection Mini-Game
Command by TheRoboticon

> A zombie plague has infected the server! Users can infect themselves with `?plague`, then infect other people with `?infect`. Those infected might want to use `?cure` to save themselves, but should be wary of a dangerous side effect!

### Requirements
 - Create the two roles `Infected` and `Uninfected`. If you'd like, you can set the `Infected` role to have some disadvantages, such as the inability to use emotes.
 - A Moderator role, for the command `?treat`. In this guide, we use the role name `Mod`, which you can change in the `?treat` file.

### Usage
 - A user starts the game by using `?plague`, which will give them the `Infected` role and remove the `Uninfected` Role. In order to prevent instances of the game erupting out of control of the moderators, it may be wise to include a specific requirement. For example, if you'd like for only Twitch Subscribers to start a game, you could add `{require:Twitch Subscribers}` to the command.
 - An `Infected` user can then infect other users with `?infect [user]`. Note the commands sends a Direct Message to the 'victim', notifying them that they have been infected.
 - `Infected` can use `?cure` to cure themselves. *This command has a 1/2 chance to mute the user, as a 'side effect'.*
 - `?treat` is a command limited to moderators, which moves all players to the `Uninfected` Role and removes the `Infected` Role.

## Roulette Mini-Game

> Feeling dangerous? Spin the revolver and take your chances with `?roulette`!

### Requirements
 - None.
 
### Usage
 - A user uses `?roulette` to play. When the command is used, the user gets a 1/6 chance to become muted for 3 minutes.
 - The command takes its name from [Russian Roulette](https://en.wikipedia.org/wiki/Russian_roulette).
 - This command will *not* work on moderators. This is due to Dynobot preventing the muting of Mods, though you can change these settings.
 
## Conclusion

Enjoyed our mini-games? Have any problems? Need help with the setup? Check out our [Discord Server](https://discord.gg/D3K3Fqz) and visit the #command-support channel for help!
 
*This guide was written by TheRoboticon*


