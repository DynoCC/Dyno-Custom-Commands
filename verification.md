# Verification

The verification system is a safeguard against spammers, advertisers and more.

---

## What is it?
The verification system makes use of three main commands and infinite code commands.  
It also makes use of a role.  
The verification system is a system that requires your users to verify that they are a human before they can start typing in your discord server.

---

## Channels
This command series makes use of a channel named #signup.  
This channel must be created for the command to work properly.

---

## Roles
First things first, you need a role called "UNVERIFIED" and give it no perms AT ALL.
Then go into every channel's settings, go to the Permissions tab and add UNVERIFIED to the list of overrides.
Once you have done that, set "Read Messages" to red/off.
The only exception for this is the #signup channel, which needs them to be able to send and receive messages.  For that channel, do not set overrides for the UNVERIFIED role.
You can also whitelist other channels for viewing, such as the rules channel.

---

## Autorole
To unverify users when they join the server, you must set up Autorole.
1. on the Modules page in the Dyno Dashboard, make sure the "Autoroles" module is enabled.
2. Go to the Autoroles page. Under "Give role on join", select UNVERIFIED.

---

## Generating codes for users to use

To use this system, you need to setup some commands that have a set action.  
You can generate codes using our awesome [Code Generator](https://dynocc.tk/CodeGenerator).  We recommend using 5-10 codes.
You then need to replace each "0" in the "?getcode" command with one of those strings.

After you have done this, you need to create a custom command with EACH of those strings.
The code needs to be
```md
{delete}
{silent}
{require:UNVERIFIED}
{require:#signup}
{!role {user} -UNVERIFIED}
```

Please note that if you have a standard role for users, the response needs to be
```md
{delete}
{silent}
{require:UNVERIFIED}
{require:#signup}
{!role {user} -UNVERIFIED, +<your role>}
```

---

## Getting codes
To get a code, you need to set up the `?getcode` command.  This can be done by going into the Dyno Dashboard, selecting your server and navigating to the Custom Commands module.
The command is 
```md
{delete}
{dm}
{require:UNVERIFIED}
{require:#signup}
{choose:{prefix}0;{prefix}0;{prefix}0;{prefix}0;{prefix}0;{prefix}0;{prefix}0}
Hello {user}, thank you for joining **{server}**! Make sure you read the requirements before using your code!  **Your code: `{choice}`** Make sure you use the code `{choice}` in #signup!
```
Note that in the `choose` line, replace the `0`s with the codes you came up with.

Please ensure that the command is "?getcode" and the response is what is above.

---

## Optional Extras

### Manually verify a user

If you want to manually verify a user, then you need to create the command "?verify" with the response 
```md
{delete}
{silent}
{!role $1 -UNVERIFIED}
```
Please note that if you have a standard role for users, then the response needs to be 
```md
{delete}
{silent}
{!role $1 +<your role>, -UNVERIFIED}
```

### Unverify a user

If a user has been acting suspiciously, you can make them verify again.
This is done by creating a "?unverify" command with response 
```md
{delete}
{silent}
{!role $1 +UNVERIFIED}
```
Please note that if you have a standard role for users, then the response needs to be 
```md
{delete}
{silent}
{!role $1 -<your role>, +UNVERIFIED}
```

### Autodelete messages in #signup
Even though the bot command messages get automatically deleted, sometimes people might try to chat in the signup channel. You can configure Dyno to automatically delete messages sent in the channel.

1. on the Modules page, make sure the "Coords Channel Mod" module is selected.
2. Go to the Coords Channel Mod page. Under "Add Coords Channel", select the #signup channel and click Add.


---

## Additional items you might want to do

You might want to execute the command "?announce #signup Welcome to our server.  We require you to verify that you are a human.  To do so, please do "?getcode" and check your DMs for a message from Dyno.  Once you have that message, you need to copy and paste your code into this chat."

Note: This page was written assuming your server's prefix is `?`.

Credit to [redstonedesigner](https://github.com/redstonedesigner)#1184 and [advaith](https://github.com/advaith1)#9121 for this page! Commands made by advaith and Olybear
