# Information Commands
Commands by Nex

These basic commands are used for teaching variable usage.
Using these commands will output specific command variables and their output.

#### `?channel-info`
This commmand outputs 3 channel specific variables along with their outputs.
 - Channel ID
 - Channel Name
 - Channel Mention

#### `?datetime-info`
This command outputs 4 time specific variables along with their outputs, in EST.
 - Current 24 hour time
 - Current 12 hour time
 - Current Date with 24 hour time
 - Current Date with 12 hour time
 
#### `?server-info`
This command outputs 7 server specific variables along with their outputs.
 - Server ID
 - Server Name
 - Server Icon Url
 - Server Member Count
 - Server Owner ID
 - Server Creation Date
 - Server Region

#### `?user-info`
This command outputs 8 user specific variables along with their outputs.
 - User ID
 - Username with Discriminator
 - Username without Discriminator
 - Discriminator
 - Nickname
 - Avatar URL
 - Account Creation Date
 - Server Join Date
 
These commands can help you improve the content of your server. For example, you could have a verification code using these variables to state:

Welcome {user.nick}! You are the {server.memberCount} user on this server!
