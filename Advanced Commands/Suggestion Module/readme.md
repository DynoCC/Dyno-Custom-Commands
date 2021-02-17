# Suggestion Module
A suggestion system designed by Nex.

> This module makes making, approving, and denying suggestions very easy and organised, using an ID system.

## Guide Markdown  
We assume you are using the default command prefix, `?`. Commands with inputs are denoted as ``?command [input]``. Commands with choice inputs are denoted as ``?command [input1/input2]``. Commands with optional inputs are denoted as ``?command (input)``.  

## Requirements
* One role - `Suggestions Manager`.
* Two channels - `#suggestions` & `#suggestion-log`.
* Add a welcome message to `#suggestions` channel explaining how to use the command.
* Set up the `#suggestion-log` channel to be only accessible to the `Suggestions Manager` role.

## Commands
* `?suggest [suggestion]` - Makes a suggestion in the `#suggestions` channel.
* `?approve [user] [suggestion-id]` - Approves a suggestion. Requires the `Suggestions Manager` role.
* `?deny [user] [suggestion-id] [reason]` - Denies a suggestion. Requires the `Suggestions Manager` role.
* `?implement [user] [suggestion-id]` - Implements a suggestion. Requires the `Suggestions Manager` role.

*To see the commands in action, visit the [Wiki](https://github.com/Strand-Custom-Commands/Strand-Custom-Commands/wiki).*
