---
title: Dyno RPG
permalink: /FunCommands/MiniGames/DynoRPG/
---

# Dyno RPG
**Dyno RPG** is a RPG Game made using Dyno Custom Commands and inspired by the infection minigame and a few other custom commands. It is planned to be a community project to be built into something everybody can enjoy. As such everyone is welcome to add their own commands to it as they desire.


## How to
A simple guide for setting up roles and channels for the commands to work as intended


- The `divine-council` channel must be only be useable by server mods as it is the channel required for using the Divine Council commands.

- When creating the roles for the commands, make sure to set the channel permissions. The roles you will need to setup channel permissions for are **Adventurer**, **Haunted**, and **Deceased**. **Haunted** and **Deceased** must be unable to chat in any channel other than `the-crypt`. **Adventurer** must be able to post messages and embed images in all channels except `the-crypt` and `divine-council`.

- The `Adventurer` role is the base role for playing Dyno RPG.

- The channel `the-crypt` was created for use with the `Deceased` role. All people who carry this role are to be considered dead and are only able to continue chatting in here until they have been raised. This channel must be hidden by default to all except the `Deceased` and the `divine-council`.

## Dyno RPG Commands

A full list of available commands for use with **Dyno RPG**

**Registration Commands**

This command is used to join the world of Avelon

 - `register`: Grants the **Adenturer** role and enters you into the forsaken world of **Avelon**.
 - `unregister`: Removes the **Adventurer** role and frees you of the forsaken world of **Avelon**.

**Attack Commands**

These commands can be used to attack other players, but be warned some come with *side effects*

 - `stab`: Stab another Adventurer 
 - `blight`: Cast Blight on another Adventurer
 - `sacrifice`: Sacrifice another Adventurer to a random deity.
 - `infect:` Infect another Advenurer.
 - `fester`: Cast Fester on another Adventurer. Can only be used by Infected Adventurers.
 - `plague`: Cast a plague infecting all Adventurers. Can only be used by infected Adventurers.
 - `deathmatch`: Challenge an Adventurer to a deathmatch.
    - `cointoss`: One of the available deathmatches. Use this command when the coin toss deathmatch is chosen.
    - `insult`: One of the available dethmatches. Use this command when the insult dethmatch is chosen.

**Medica Commands**

These commands can be used to heal status ailments.

 - `treat`: Cure another Adventurer of all ailments
 - `cure`: Cure yourself of all ailments
 - `raise`: Raise another Adventurer from the dead

**Divine Commands**

These commands can only be used by the Divine Council *[aka server mods]*

 - `divinecure`: Cures all Adventurers of all ailments.
 - `dyno-rpg [enable|disable]`: Enable or Disable **all** Dyno RPG Commands.


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
