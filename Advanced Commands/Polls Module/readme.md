# Polls Module
A polls command system designed by Roboticon and updated by Nex.  

> This command system makes doing polls organised and ordered.

## Guide Markdown  
We assume you are using the default command prefix, `?`. Commands with inputs are denoted as ``?command [input]``. Commands with choice inputs are denoted as ``?command [input1/input2]``. Commands with optional inputs are denoted as ``?command (input)``.

## Requirements
* Four roles - `I Voted For Option 1!`, `I Voted For Option 2!`, `Polls` & `Polls Manager`.
* One channel - `#polls`.
* Make the `Polls` role unmentionable.

## Commands
* `?pollstart [option 1] [option2] [message]` - Starts a poll. Requires the `Polls Manager` role.
* `?pollclose [results]` - Closes the on-going poll. Requires the `Polls Manager` role.
* `?pollcount` - Gives the results of the on-going poll. Requires the `Polls Manager` role.
* `?op1` - Used to vote for Option 1.
* `?op2` - Used to vote for Option 2.

*To see the correct usage format of the commands, visit the [Wiki](https://github.com/Strand-Custom-Commands/Strand-Custom-Commands/wiki).*

<!---
### Note
This module is pretty hard to setup and configure so if you need help with anything, join the [Dyno support server](https://discord.gg/dyno).
--->
