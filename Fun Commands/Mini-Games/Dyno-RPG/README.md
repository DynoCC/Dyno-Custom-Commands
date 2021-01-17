---
title: Dyno RPG
permalink: /FunCommands/MiniGames/DynoRPG/
---

# Dyno RPG
Otherwise called **Avelon RPG**, Dyno RPG is a RPG Game made using Dyno CC and inspired by the infection minigame and a few other custom commands. It is planned to be a community project to be built into something everybody can enjoy. As such everyone is welcome to add their own commands to it as they desire.


## How to
A simple guide for setting up roles and channels for the commands to work as intended

 - The `Adventurer` role is the base role for playing Dyno RPG. As such it is suggested to use the role selection menu when adding the commands to make the commands require it.

 - Deathmatch Commands should be allowed only in `the-deathpits`.


- Divine Council Commands should be limited to serverMod only and only allowed to be used in `divine-council`, while the response can preferably be set to `world-gates` if desired.

- `Plugue` and `Fester` should only be useable if the person calling them is `Infected`.

- Divine Council is not actually a role, it's a nickname for serverMods. As such I decided not to make a separate role for it.

 - The `rpg-cmds` command should be accessible to `Adventurer` roles only, while the `register` command should be accessible to everyone in the server so people can join **Avelon**.

 - All commands should preferably also be set to both silent and delete so as to prevent anyone from knowing who is doing what.


## Avelon Commands
A Full list of available commands for use with **Avelon RPG**

**Registration Commands**

This command is used to join the world of Avelon

 - `register`: Grants the **Adenturer** role and enters you into the forsaken world of Avelon

**Attack Commands**

These commands can be used to attack other players, but be warned some come with *side effects*

 - `blight`: Cast Blight on another Adventurer
 - `fester`: Cast Fester on another Adventurer
 - `infect`: Cast infect on another Adventurer
 - `curse`: Cast a curse on another Adventurer
 - `plague`: Cast a plague infecting all Adventurers
 - `stab`: Stab another Adventurer
 - `sacrifice`: Sacrifice another Adventurer to a random deity
 - `deathmatch`: Challenges a randomly chosen deathmatch
   - `cointoss`: Used in the coin toss deathmatch, generate random cause of death
   - `insult`: Used in the insult deathmatch, generates a random insult

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
- `Cursed`
- `Sacrificed`
- `Adventurer`

As well as the following channels:


- `world-gates`
- `the-crossroads`
- `the-bloodfields`
- `the-deathpit`
- `castle-grounds`
- `castle-courtyard`
- `sacrificial-offerings`
- `divine-council`

### Usage
This guide assumes that your prefix is `?`. We will use `[input1]` and `[input2]` for the user arguments.

A user enters the game by using `?register`, which will give them the Adveturer role and send an introduction message into `world-gates`. This requires that the channel `world-gates` exists in the server. 

Once the Adventurer role has been obtained, a user can begin playing by typing `?infect [input1]` to infect another user. The infected user will obtain the `infected` role and in doing so the ability to choose to either spread a plague by typing `?plague` or fester another user by typing `?fester [input1]`.

More attacks that can be done are Blight, Curse, and Sacrifice by typing `?blight [input1]`, `?curse [input1]`, or `?sacrifice [input1]`.
Adventurers can aid eachother by typing `?treat [input1]` to cure each other of status ailments, `?raise [input1]` to raise another Adventurer from the dead, or they can heal themselves by typing `?cure` to cure their own status ailments.

Adventurers can also start a deathmatch with another Adventurer by typing `?deathmatch [input1]`. This will select a deathatch at random.
 - For the insult deathmatch, simply type `?insult [input1]` and it will respond with a random hillariously overexagerrated insult.
 - For the cointoss deathmatch simply type `?cointoss` and it will respond with a random somewhat hillarious death certificate.

ServerMods and up are reffered to as the Divine Council and can occasionally send down a divine blessing by typing `?divinecure`. This will cure raise and heal all Adventurers.

### Notes

- It is suggested that the `divine-council` channel be useable **ONLY** by serverMods as it is the channel required for using the Divine Council commands.

- When creating the roles for the commands, make sure to determine which roles have which effects. The effects will be entirely up to the ones setting it up, so know that this RPG is best when each role has a specific effect on the one carrying it.

- The `Adventurer` role is the base role for playing Dyno RPG. As such it is suggested to use the role selection menu when adding these commands to make the commands require it.

***This is a ongoing project and will have more commands added over time. Anyone who wishes to contribute their own commands would of course be welcome to do so.***
