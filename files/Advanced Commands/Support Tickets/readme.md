# Support Tickets
A command group designed by Sobriquet#0001.

> This command group allows the use of Support Tickets in your server and is primarily designed for Support services on busy servers.  
> Support can review tickets in a ticket queue, then accept or deny them with simple commands.  
> Accepting a ticket allows the user who posted it access to a private Support Room.  
> This makes it easier to moderate support services and allows personal conversations with users.

## Guide Markdown
We assume you are using the default command prefix, `?`. Commands with inputs are denoted as ``?command [input]``. Commands with choice inputs are denoted as ``?command [input1/input2]``. Commands with optional inputs are denoted as ``?command (input)``.

## Requirements
- Three roles, `Pending`, `Ticket`, and `Support`.
- Three channels, `#support-room`, `#support-requests`, and `#ticket-queue`.
 - Set up the `#support-room` channel to be only accessible to those with the `Support` role and the `Ticket` role.
 - Add a welcome message the `#support-room` channel explaining its use and pin it.
 - Set up the `#ticket-queue` channel to be only accessible to the `Support` role.
 - Add a message to the `#support-requests` channel explaining its use and pin it.

## Commands
* `?ticket [ticket]` - Posts a ticket in the ticket queue. A user who has posted a ticket cannot post another until it is reviewed. 
* `?accept [user]` - Accepts a user's ticket. Requires the `Support` role. Can only be used in the `#ticket-queue` channel.  
* `?deny [user]` - Denies a user's ticket. Requires the `Support` role. Can only be used in the `#ticket-queue` channel.  
* `?close` - Resets the support room. Can only be used in the `#support-room` channel.  

Currently Bugged:  
* `?away` - Locks the `#support-requests` channel.  
* `?back` - Reopens the `#support-requests` channel.

### Note
There is currently a bug with the `?lock` command and reasons. The `?away` and `?back` commands are being updated to reflect this.
