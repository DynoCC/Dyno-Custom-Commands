# Mini-Games

## Caesar Mini-Game
Command by Amosharper

> A simple game where only one person can hold the role of ``Caesar``, and anyone can claim it. Requires an existing role of ``Caesar``, preferably with a distinct color. Could give ``Caesar`` special privileges, like the ability to post embeds, or use external emoji, or to mute other users. Since the calling message is deleted (to cut down on bot spam), you'll need to document the command somewhere.

#### Requirements
 - Create the role ``Caesar``. If you'd like, you can give it specific permissions, as per the description above.
 - (Optional) Add requirements to the command forcing it to be used in a specific channel. For example, to force the command to be used only in the channel, ``#throne-room``, place in the command ``{require:#throne-room}``.

#### Usage
 - The syntax for this command is ``?crownme``.
 - A member who does not currently hold the role of ``Caesar`` can use the command, which moves them to the role of Caesar.
 - When this command is run, it removes the ``Caesar`` from any other users.
