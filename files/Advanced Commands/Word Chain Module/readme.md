# Last Word Module
A single-command mini-game designed by Sobriquet#0001.

> This single-command mini-game is quite simple. The user inputs a phrase, with the last word in the phrase becoming the first word of the next one.
> The custom command will check if the phrase is valid. If no input is provided, it will output the last word and phrase used.

## Guide Markdown  
We assume you are using the default command prefix, `?`. Commands with inputs are denoted as ``?command [input]``. Commands with choice inputs are denoted as ``?command [input1/input2]``. Commands with optional inputs are denoted as ``?command (input)``.

## Requirements
* You should run the following commands.
  - ``?addrole Start``
  - ``?role 155149108183695360 +Start``
* Optional: You can use the StrandCC ``?setup`` command to setup this module.

## Commands
* ``?last (phrase)`` - If a valid input is entered, the command will set the new phrase and word, storing it as a role on Dyno. If not, the command will output the last phrase and word used.