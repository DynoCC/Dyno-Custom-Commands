---
canonical_url: https://dynocc.xyz/variables
layout: amp
---

# Variables
You can use variables in your autoresponders and custom commands to make them powerful!

## Simple Variables
You can use these in autoresponders and custom commands.

- `{user}`: The user calling the command. Eg: Hello `{user}!`
- `{server}`: The server name
- `{channel}`:  The channel name
- `{@user}`:  Mention a user by their username (not nickname), replace user with username. Eg: - `{@Nooblance}`
- `{&role}`:  Mention a role by name, replace role with the role name. Eg: - `{&Gamers}, We're streaming now!`
- `{#channel}`:  A channel link, replace channel with the name of the channel you want to link. Eg: Use - `{#testing} for all bot testing.`
- `{everyone}`:  `@everyone`
- `{here}`:  `@here`

## More Variables
These variables are more complex, and only work in custom commands.

### `{user}` Variables
- `{user.id}`:  User's id
- `{user.name}`:  User's nickname including the discrim
- `{user.username}`:  User's username
- `{user.discriminator}` aka `{user.discrim}`:  User's discriminator
- `{user.nick}`:  User's nickname excluding the discrim
- `{user.game}`:  User's current game (if nothing, gets the last played game)
- `{user.avatar}`:  User's avatar
- `{user.mention}`:  Mentions the user
- `{user.createdAt}`:  User's registeration date
- `{user.joinedAt}`:  User's join date

### `{server}` Variables
- `{server.id}`:  Server's id
- `{server.name}`:  Server's name
- `{server.icon}`:  Server's icon
- `{server.memberCount}`:  Amount of members on the server
- `{server.ownerID}`:  Owner's id
- `{server.createdAt}`:  Server's creation date
- `{server.region}`:  Server region

### `{channel}` Variables
- `{channel.id}`:  Channel id
- `{channel.name}`:  Channel name
- `{channel.mention}`:  Channel mention

### `{time}`/`{date}` Variables
Note: This will be in EST unless you set the time zone in the Premium dashboard.

- `{time}`:  Current 24 hour time
- `{time12}`:  Current 12 hour time
- `{date}`:  Current date
- `{datetime}`:  Current date with the 24 hour time
- `{datetime12}`:  Current date with the 12 hour time

### Advanced Variables
Note: Most of these must be on separate lines

- `{noeveryone}`:  Disables `@everyone` in command
- `{prefix}`:  Output command prefix for server
- `{delete}`:  Delete command trigger after, example: - `{delete} I am Dyno`
- `{silent}`:  Silents the bot's default response to a command used, example: - `{silent} {!role {user} Humans}`
- `$N` - returns a command argument, example: `You chose $1`
- `$N+` - returns a command argument and all the arguments after that, example: `You chose $1+`
- `{!command}`:  execute a bot command, example: - `{!role $1 Regulars}`
- `{require:role}`:  Set required roles or serverMod to use command, example: - `{require:Accomplices} or - `{require:serverMod}
- `{require:#channel}`:  Set required channel to use command in, example:- `{require:#batcave} This is the batcave.`
- `{not:role}`:  Blacklist Role from using command, example:- `{not:Lost Privileges}`
- `{not:#channel}`:  Blacklist from being able to use command in said channel, example:- `{not:#general}`
- `{respond:#channel}`:  Set the channel the command responds in, example: - `{respond:#announcements} Announcements woo!`
- `{dm}`:  DM the bot response, example: - `{dm} I just DMed you!`
- `{dm:user}`:  DMs the bot response to a specified user, example: - `{dm:Nooblance} I just DMed the mighty Lance!`
- `{choose:option1;option2;option3}`:  List of items to randomize, example: - `{choose:pie;cake;icecream;ban hammer}`
- `{choice}`:  Placement for `{choose}` variable, example: `{My favorite desert is {choice}`

This list was copied from the Dyno Premium dashboard, then formatted and edited by DCC.
