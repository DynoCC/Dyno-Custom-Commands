# Poll System
This guide will teach you how to set up the Poll System, developed by TheRoboticon. *If you have any problems, head to the Dyno Custom Commands Server and send a message to the @TheRoboticon#8358*

## Guide Markdown:
We assume that you are using the default command prefix, ``?``. Inputs will be written as ``[input]``. Choice inputs will be denoted as ``[input1/input2]``, respectively.

## Requirements
- A Channel to post important things in. We've called this channel ``#info-and-news``, but you can call it whatever you want- just edit the command as well.
- Two Voting Roles, ``Option1`` and ``Option2``. Again, you can name it whatever you want, just make sure to modify the command appropriately.
- A Moderator Role. In the current code, we used Moderator as our role name.

## List of Commands and Permissions

-``?poll`` (Requires: Moderator)  
-``?op1`` and ``?op2``  
-``?pollcount`` (Requires: Moderator)  
-``?pollclose`` (Requires: Moderator)  

## Command Use and Syntax

- ``?poll`` creates a new poll in your announcements channel.  
  - Use the format ``?poll [option one] [option two] [question]``  
  - For example, the poll 'Do you like Sandwiches?' would be written as follows: ``?poll Yes No Do you like Sandwiches?``  
  
- ``?op1`` and ``?op2`` are the two voting commands.  
  - Following the example above, a user that enjoys sandwiches would type ``?op1`` to vote Yes.  
  - Note that once someone has voted, they cannot change their choice- the command will not work for them until you have closed the poll.
  
- ``?pollcount`` posts the current poll results in the channel you use it in.  
  - This will show the members of the two roles, ``Option1`` and ``Option2``.  
  - In rare cases there may be too many members to show in the list. For this, use the default command ``?roleinfo [option1/option2]``.

- ``?pollclose`` ends the current poll and removes all users from the roles ``Option1`` and ``Option2``, then announces the result.
  - Use the format ``?pollclose [results]``  
  - For example, if most people voted yes for Sandwiches, you would might say ``?pollclose Looks like y'all like Sandwiches!``  
  - Note that the bot will also output a message noting the roles that are being removed. This is normal- you can use this command in a separate channel to hide the output.
  
## Conclusion

Congratulations on installing the new Poll Command system! Maybe you could ask your server members if they enjoy sandwiches as your first poll?

Hopefully this guide was helpful (*It better be, I spent a good 30 minutes on it*). If you have any questions, head over to the Dyno Custom Command server and ask the support staff for help, and we'll gladly help you through the process.
