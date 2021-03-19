---
title: Dyno RPG
permalink: /FunCommands/MiniGames/DynoRPG/
---

# Dyno RPG
Otherwise called **Avelon RPG**, Dyno RPG is a RPG Game made using Dyno CC and inspired by the infection minigame and a few other custom commands. It is planned to be a community project to be built into something everybody can enjoy. As such everyone is welcome to add their own commands to it as they desire.


## How to
A simple guide for setting up roles and channels for the commands to work as intended

 - Run the `setup` command in your guild. Make sure you have the required permissions. This command will automatically create all required channels, and roles.
 - Make any channel specific changes yourself. You can customize the permissions of each role according to your own preferences from within discord.



## Avelon Commands
A Full list of available commands for use with **Avelon RPG**

**Registration Commands**

This command is used to join the world of Avelon

 - `register`: Grants the **Adenturer** role and enters you into the forsaken world of Avelon

**Attack Commands**

These commands can be used to attack other players, but be warned some come with *side effects*

 - `stab`: Stab another Adventurer 
 - `blight`: Cast Blight on another Adventurer
 - `sacrifice`: Sacrifice another Adventurer to a random deity.
 - `infect:` Infect another Advenurer.
 - `fester`: Cast Fester on another Adventurer. Can only be used by Infected Adventurers.
 - `plague`: Cast a plague infecting all Adventurers. Can only be used by infected Adventurers.


**Medica Commands**

These commands can be used to heal status ailments.

 - `treat`: Cure another Adventurer of all ailments
 - `cure`: Cure yourself of all ailments
 - `raise`: Raise another Adventurer from the dead

**Divine Commands**

These commands can only be used by the Divine Council *[aka serverMods]*

 - `divinecure`: Cures all Adventurers of all ailments


### Requirements
For this to work you will need the following roles in your guild:

- `Festered`
- `Blighted`
- `Bleeding`
- `Infected`
- `Deceased`
- `Haunted`
- `Cursed`
- `Sacrificed`
- `Adventurer`

As well as the following channels:


- `world-gates`
- `the-crossroads`
- `the-crypt`
- `the-bloodfields`
- `the-deathpit`
- `castle-grounds`
- `castle-courtyard`
- `sacrificial-offerings`
- `divine-council`



### Notes

- It is suggested that the `divine-council` channel be both visible **AND** useable **ONLY** by serverMods as it is the channel required for using the Divine Council commands.

- When creating the roles for the commands, make sure to determine which roles have which effects. The effects will be entirely up to the ones setting it up, so know that this RPG is best when each role has a specific effect on the one carrying it.

- The `Adventurer` role is the base role for playing Dyno RPG.

- The channel `the-crypt` was created for use with the `Deceased` role. All people who carry this role are able to continue chatting in here until they have been raised. This channel should be hidden by default to all except the `Deceased` and the `divine-council`.

- The `rpg-setup` command will create the required roles and channels for you, but will not alter or set their permissions. You will need to do this part yourself.
