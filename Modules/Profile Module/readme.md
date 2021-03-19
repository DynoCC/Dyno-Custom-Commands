# Profile Module
A command group designed by the Sobriquet#0001.

> This module combines the default Tags Module included in Dyno with the power of Custom Commands to create a simple profile system for users.  
> Users will be able to set a 150-character description and view other profiles, while moderators are able to remove and edit profiles deemed disruptive or unwanted.  
> This module group features a master switch disabling the system's profiles while still allowing moderators to remove profiles.

## Guide Markdown  
We assume you are using the default command prefix, `?`. Commands with inputs are denoted as ``?command [input]``. Commands with choice inputs are denoted as ``?command [input1/input2]``. Commands with optional inputs are denoted as ``?command (input)``.

## Requirements
* The default tag system in Dyno needs to be enabled. Use `?module tags` to enable the tag system.  
* You should then run the following commands.  
  - ``?tag create pr-setinfo *You can set your profile information with `?setinfo [information]`.*``
  - ``?tag create pr- **Error:**``  
  - ``?tag create pr--info **User not found.**``
* Alternatively, you can use the StrandCC ``?setup`` command to setup the module.

## Commands
* `?setinfo [information]` - Sets the text displayed on your profile.  
* `?profile (user)` - Views a user's profile, or your own if none is specified.
* `?delprofile [user]` - Deletes a user's profile. Requires Server Moderator.  
* `?edprofile [user] [information]` - Edits a user's profile. Require Server Moderator.
* `?profiles [enable/disable]` - Enables/disables the profile module. The ``?delprofile`` command will not be disabled. Requires Server Moderator.