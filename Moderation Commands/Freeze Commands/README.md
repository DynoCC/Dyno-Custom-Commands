---
canonical_url: 'https://dynocc.xyz/freeze'
permalink: /freeze
---

# Freeze Command Docs
How to set up the Freeze command:

First, add the Freeze commands: [freeze](https://github.com/DynoCC/Dyno-Custom-Commands/blob/master/Freeze.txt) and [unfreeze](https://github.com/DynoCC/Dyno-Custom-Commands/blob/master/unfreeze.txt)

Then, run `?addrole freeze #ffffff` in your server. This will do some of the setup work for you.

Next, go to the settings for each channel, and set `freeze` to `can't send messages`, as shown:

![Freeze Perms](https://cdn.discordapp.com/attachments/252296452708106240/349807958378414084/Screen_Shot_2017-08-20_at_9.26.10_PM.png)

(Of course we don't use light theme, we painfully went through the ordeal of turning on light theme to make this image blend in better with the rest of the page.)

Once you complete setting that for each channel, the freeze command should be ready. Simply use `?freeze` to freeze the server, and `?unfreeze` to revert to normal.
Note that on large servers it may take a while to freeze everyone, up to a minute.
Administrators are not affected by freezes.

If you want to customize the freeze command (maybe excludes certain roles), please contact us on Discord [here](https://discord.gg/8xBag8Q).

Note: If your server has a different prefix than `?`, you will need to use that prefix in place of `?` in this documentation.

Documentation written by advaith#9121.
