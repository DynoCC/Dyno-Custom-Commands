# Verification Module
A commmand group designed by Sobriquet#0001.

> This command group implements a lottery system with a thousand combinations, as a well as a master switch for the module.  
> This module can help you run giveaways within your server.

## Guide Markdown  
We assume you are using the default command prefix, `?`. Commands with inputs are denoted as ``?command [input]``. Commands with choice inputs are denoted as ``?command [input1/input2]``. Commands with optional inputs are denoted as ``?command (input)``.

## Requirements
* One channel: ``#lottery-tickets``, which has send message permissions denied for ``@everyone``.
* One role: ``Lottery Winner``, which will be given to the winning user.

## Commands
* ``?numbers [num] [num] [num]`` - Posts the user's lottery number in the chat.
* ``?draw`` - Selects the winning combination and filters for it. Can only be used in ``#lottery-tickets``.
* ``?award [user]`` - Gives the winner the lottery role and clears the ``#lottery-tickets`` channel. Can only be used in ``#lottery-tickets``.
* ``?lottery [enable/disable]`` - Enables or disables the lottery module.