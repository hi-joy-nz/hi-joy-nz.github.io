<link href="style.css" rel="stylesheet">
<link rel="shortcut icon" type="image/x-icon" href="icon.ico">
<title>Joy | SafeBot Docs</title>

# 📋 SafeBot Documentation
Documentation for the SafeBot Discord Bot, a private Discord bot for the [Safe Haven Discord server](https://discord.gg/BcuRXcBasz)

SafeBot is made with [discord.py](https://discordpy.readthedocs.io/en/stable/), and is developed solo by [hi.joy](https://hi-joy-nz.github.io/)

# 📖 Table of contents
**[-- Commands --](https://hi-joy-nz.github.io//SafeBot/Docs#%EF%B8%8F-commands)** <br>
<ins>**General**</ins> <br>
[Help](https://hi-joy-nz.github.io//SafeBot/Docs#help-command)<br>
[Suggest](https://hi-joy-nz.github.io//SafeBot/Docs#suggest-a-feature)<br>
**<ins>Fun</ins>** <br>
[About](https://hi-joy-nz.github.io//SafeBot/Docs#about-user) <br>
[Coinflip](https://hi-joy-nz.github.io//SafeBot/Docs#coinflip)<br>
[Random colour](https://hi-joy-nz.github.io//SafeBot/Docs#generate-a-random-colour)<br>
[Spotify search](https://hi-joy-nz.github.io//SafeBot/Docs#search-for-a-song-on-spotify)<br>
**<ins>Points</ins>** <br>
[Balance](https://hi-joy-nz.github.io//SafeBot/Docs#points-balance) <br>
[Daily](https://hi-joy-nz.github.io//SafeBot/Docs#claim-daily-points)<br>
[Work](https://hi-joy-nz.github.io//SafeBot/Docs#work-for-points)<br>
**<ins>Pokemon</ins>** <br>
[Pokemon collection](https://hi-joy-nz.github.io//SafeBot/Docs#pokemon-collection)<br>
[Pokemon info](https://hi-joy-nz.github.io//SafeBot/Docs#pokemon-information)<br>
[Pokemon spawn](https://hi-joy-nz.github.io//SafeBot/Docs#spawn-a-pokemon)<br>
[Pokemon spawns](https://hi-joy-nz.github.io//SafeBot/Docs#check-the-pokemon-that-spawn-in-an-area)<br>
**<ins>Tickets</ins>** <br>
[Ticket add](https://hi-joy-nz.github.io//SafeBot/Docs#add-a-user-to-a-ticket)<br>
[Ticket close](https://hi-joy-nz.github.io//SafeBot/Docs#close-a-ticket)<br>
[Ticket create GUI](https://hi-joy-nz.github.io//SafeBot/Docs#create-ticket-gui)<br>
[Ticket remove](https://hi-joy-nz.github.io//SafeBot/Docs#ticket-remove)<br>
**<ins>Server moderation</ins>** <br>
[Mute](https://hi-joy-nz.github.io//SafeBot/Docs#mute-a-user)<br>
[Set slowmode](https://hi-joy-nz.github.io//SafeBot/Docs#set-channel-slowmode)<br>
[Staff help](https://hi-joy-nz.github.io//SafeBot/Docs#staff-help-command)<br>
[Unmute](https://hi-joy-nz.github.io//SafeBot/Docs#unmute-a-user)<br>
**<ins>Bot management</ins>** <br>
[Change points](https://hi-joy-nz.github.io//SafeBot/Docs#change-points-of-a-user) <br>
[Change points (all)](https://hi-joy-nz.github.io//SafeBot/Docs#change-points-of-all-users) <br>
[Set bot status](https://hi-joy-nz.github.io//SafeBot/Docs#set-the-bots-status)

**[-- Features --](https://hi-joy-nz.github.io//SafeBot/Docs#-features)** <br>
[Starboard](https://hi-joy-nz.github.io//SafeBot/Docs#starboard)<br>
[Ticketing](https://hi-joy-nz.github.io//SafeBot/Docs#ticketing)
 
# 🎛️ Commands

## About user
**Version added:** 1.0.0 <br>
**Description:** Display details about a user.

**Usage:** `/about <user>` <br>
**Permissions required:** None

<table>
<tr><th>Name</th><th>Description</th></tr>
<tr><td>user</td><td>The user to provide details about. Must be a user in the current server.</td></tr>

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| user | The user to provide details about. Must be a user in the current server.| 


*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)* 


## Points balance
**Version added:** 1.0.0 <br>
**Description:** Display the points balance of a user or the command user. <br>

**Usage:** `/balance [user]` <br>
**Permissions required:** None <br>

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **(Optional) user** | The user to display the balance of. Must be a user in the current server. |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Change points of a user
**Version added:** 1.0.0 <br>
**Description:** Change the points balance of a user with an active balance by a certain amount. 

**Usage:** `/change_points <user> <change>` <br>
**Permissions required:** Bot admin 

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **user** | The user to change the points balance of. Must be a user in the server. |
| **change** | The amount of points to change `user`'s balance by. Must be an integer, can be positive or negative. |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Change points of all users
**Version added:** 1.0.0 <br>
**Description:** Change the points balance of all users with an active balance by a certain amount.

**Usage:** `/change_points_all <change>` <br>
**Permissions required:** Bot admin

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **change** | The amount of points to change all balances by. Must be an integer, can be positive or negative. |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Coinflip
**Version added:** 1.0.0 <br>
**Description:** Flip a coin, it can land on heads or tails.

**Usage:** `/coinflip` <br>
**Permissions required:** None 

**Parameters:** <br> None

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Claim daily points
**Version added:** 1.0.0 <br>
**Description:** Claim 350 free points once every 24 hours.

**Usage:** `/daily` <br>
**Permissions required:** None

**Parameters:** <br> None

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Help command
**Version added:** 1.0.0 <br>
**Description:** Display a list of commands

**Usage:** `/help` <br>
**Permissions required:** None

**Parameters:** <br> None

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Mute a user

**Version added:** 1.0.0 <br>
**Description:** Mute a user for a set period of time.

**Usage:** `/mute <user> <length> <reason>` <br>
**Permissions required:** Mute members

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **user** | A user in the current server that is not already muted.| 
| **length** | Time in minutes the user should be muted for. |
| **reason** | The reason for muting the user. |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Pokemon collection
**Version added:** 1.0.0 <br>
**Description:** Displays your Pokemon collection.

**Usage:** `/pokemon_collection [filter]` <br>
**Permissions required:** None

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **(Optional) filter** | Filter your collection to display only Pokemon that meet certain criteria. Options: <br> |
| | **Shiny** \| Filter for shiny Pokemon |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Pokemon information
**Version added:** 1.0.0 <br>
**Description:** Displays details about a Pokemon in your collection.

**Usage:** `/pokemon_info <number>` <br>
**Permissions required:** None

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **number** | Collection number of the Pokemon in your collection. Must be an integer within your collection. |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Spawn a Pokemon

**Version added:** 1.0.0 <br>
**Description:** Spawn a wild Pokemon in a certain area once every two minutes.

**Usage:** `/pokemon_spawn <area>` <br>
**Permissions required:** None

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **area** | The area in which you want to spawn a Pokemon. Each area has a different list of Pokemon that can spawn. Options: |
| | Farfetch'd Fields |
| | Shaded Forest |
| | Cliff's Cave |
| | Danger Desert |
| | Blue Beach |
| | Blue Sea |
| | Cloudy Sky |
| | Mount Magma |
| | Dark Gravestones |
| | Science Lab |
| | Myndflike City |
| | Snowfield Forest |
| |Galactic Edge | 
| |Event |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Check the Pokemon that spawn in an area

**Version added:** 1.0.0 <br>
**Description:** Display a list of Pokemon that spawn in an area sorted by rarity.

**Usage:** `/pokemon_spawns <area>` <br>
**Permissions required:** None

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **area** | The area in which you want to check what Pokemon spawn. Each area has a different list of Pokemon that can spawn. Options: |
| | Farfetch'd Fields |
| | Shaded Forest |
| | Cliff's Cave |
| | Danger Desert |
| | Blue Beach |
| | Blue Sea |
| | Cloudy Sky |
| | Mount Magma |
| | Dark Gravestones |
| | Science Lab |
| | Myndflike City |
| | Snowfield Forest |
| |Galactic Edge | 
| |Event |


*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Generate a random colour
**Version added:** 1.0.0 <br>
**Description:** Generate a random colour. This will provide both the colour's Hex code and RGB value. 

**Usage:** `/random_colour` <br>
**Permissions required:** None

**Parameters:** <br> None

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*


## Set the bot's status
**Version added:** 1.0.0 <br>
**Description:** Set the bot's status to a certain value 

**Usage:** `/set_bot_status <status_type> <text>` <br>
**Permissions required:** Bot admin

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **status_type** | The type of status. Options: |
| | Listening to - Set status to "Listening to \<text>" |
| | Playing - Set status to "Playing \<text>" |
| | Watching - Set status to "Wathcing \<text>" |

**text** | Text to show in status. Example: `Playing <text>`

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Set channel slowmode
**Version added:** 1.0.0 <br>
**Description:** Set the current channel's slowmode

**Usage:** `/set_slowmode <cooldown>` <br>
**Permissions required:** Manage messages

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **cooldown** | Time in seconds to set the channel's slowmode to |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Search for a song on Spotify
**Version added:** 1.0.0 <br>
**Description:** Searches Spotify fro a prompt and returns the top song

**Usage:** `/spotify_search` <br>
**Permissions required:** None

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **search** | Search spotify for this term |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Staff help command
**Version added:** 1.0.0 <br>
**Description:** Display a list of commands for server staff and bot admins

**Usage:** `/staff_help` <br>
**Permissions required:** None

**Parameters:** <br> None

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Suggest a feature
**Version added:** 1.0.0 <br>
**Description:** Suggest a feature or change, or report a bug to the developer

**Usage:** `/suggest` <br>
**Permissions required:** None

**Parameters:** <br> None, but will open a model (form) that must be filled in

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Add a user to a ticket
**Version added:** 1.0.0 <br>
**Description:** Adds a user to the current ticket

**Usage:** `/ticket_add <user>` <br>
**Permissions required:** None, but must be in a ticket

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **user** | The user to add to the current ticket. Must be a user that is in the server but not already in the current ticket |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Close a ticket
**Version added:** 1.0.0 <br>
**Description:** Close the currently open ticket.

**Usage:** `/ticket_close` <br>
**Permissions required:** None, but must be in a ticket

**Parameters:** <br> None

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Create ticket GUI
**Version added:** 1.0.0 <br>
**Description:** Send the 'open a ticket' GUI to the current channel.

**Usage:** `/ticket_create_gui` <br>
**Permissions required:** Manage Server

**Parameters:** <br> None

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Ticket remove
**Version added:** 1.0.0 <br>
**Description:** Remove a user from the current ticket.

**Usage:** `/ticket_remove <user>` <br>
**Permissions required:** Kick members, and must be in a ticket

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **user** | The user to remove from the current ticket. Must be a member in the server who is already in the ticket. |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Unmute a user

**Version added:** 1.0.0 <br>
**Description:** Unmute a muted user

**Usage:** `/unmute <user> <reason>` <br>
**Permissions required:** Mute members

**Parameters:** <br>

| Name | Description |
| ------ | ------ |
| **user** | User to be unmuted. Must be a member of the server that is currently muted |
| **reason** | Reason for unmuting the user |

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*



## Work for points
**Version added:** 1.0.0 <br>
**Description:** Go to 'work', return in two hours to claim 80-120 points.

**Usage:** `/work` <br>
**Permissions required:** None

**Parameters:** <br> None

*[Return to Table of Contents](https://hi-joy-nz.github.io//SafeBot/Docs#-table-of-contents)*


# ⭐ features

## Starboard

**Version added:** 1.0.0 <br>
**Description:** When a message recieves three or more ⭐ reactions, it will be sent to the starboard channel

**Usage:** React to a cool message with the ⭐ emoji, once 3 people react with that, it will be sent to the starboard! <br>
**Permissions required:** Add reactions


## Ticketing

**Version added:** 1.0.0 <br>
**Description:** Users can open a private channel with staff to discuss issues or questions.

**Usage:** Users simply click the 'open ticket' button in the designated ticket support channel. They will then get a private channel to talk to staff through. <br>
**Permissions required:** None
