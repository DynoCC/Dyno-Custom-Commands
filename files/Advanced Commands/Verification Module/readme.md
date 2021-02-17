# Verification Module
A commmand group designed by Nex.

> This command group implements an advanced verification system using image verification and codes.
> By using this, you can easily prevent raids from occuring by creating a system difficult for bots to navigate. 

## Guide Markdown  
We assume you are using the default command prefix, `?`. Commands with inputs are denoted as ``?command [input]``. Commands with choice inputs are denoted as ``?command [input1/input2]``. Commands with optional inputs are denoted as ``?command (input)``.

## Requirements
* One channel, `#welcome`, which contains any rules and information joining users should read.
* Inside `#welcome`, make sure to tell the user to use `?dmimage` to get their code.
* One role, `Newcomer`, which has been denied Read Message permissions in all channels except welcome.
* The `Newcomer` role should be given when a user joins. You should use the [Autoroles module](https://github.com/Strand-Custom-Commands/Strand-Custom-Commands/blob/master/Commands/Verification%20Module/readme.md#autoroles-modules-setup) for this.

## Autoroles Module Setup
**1.** Go to https://dyno.gg and click on `Manage A Server`.  
**2.** Select your server.  
**3.** Click on `Autoroles` under the `Module Settings` section.  
**4.** Select the `Newcomers` role in the `Select Role`.  
**5.** Click on `Add`.  

## Commands
* `?dmimage` - Sends a DM to the user with a random image.
* `?[password]` - Verifies the user.   
* `?verify [user]` - Verifies another user. Can be only used by Mods.
* `?unverify [user]` - Unverifies another user. Can be only used by Mods.

*Note that `?[password]` is just a placeholder for any of the [10 codes](https://github.com/Strand-Custom-Commands/Strand-Custom-Commands/blob/master/Commands/Verification%20Module/codes.md) available.
You should not add `?[password]` as an actual custom command.*

*To see the commands in action, visit the [Wiki](https://github.com/Strand-Custom-Commands/Strand-Custom-Commands/wiki).*
