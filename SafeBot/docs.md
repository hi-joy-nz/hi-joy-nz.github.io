# 📋 SafeBot Documentation

<br>

# 📖 Table of contents
- [Commands](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#%EF%B8%8F-commands)
  - [About](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#about-user)
  - [Balance](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#points-balance)
  - [Change points](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#change-points-of-a-user)
  - [Change points (all)](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#change-points-of-all-users)
  - [Coinflip](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#coinflip)
  - [Daily](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#claim-daily-points)
  - [Help](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#help-command)
  - [Mute](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#mute-a-user)
  - Pokemon
    - [Collection](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#pokemon-collection)
    - [Info](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#pokemon-information)
    - [Spawn](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#spawn-a-pokemon)
    - [Spawns](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#check-the-pokemon-that-spawn-in-an-area)
  - [Random colour](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#generate-a-random-colour)
  - [Set bot status](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#set-the-bots-status)
  - [Set slowmode](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#set-channel-slowmode)
  - [Spotify search](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#search-for-a-song-on-spotify)
  - [Staff help](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#staff-help-command)
  - Tickets
    - [Add](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#add-a-user-to-a-ticket)
    - [Close](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#close-a-ticket)
    - [Create GUI](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#create-ticket-gui)
    - [Remove](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#ticket-remove)
  - [Unmute](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#unmute-a-user)
- [Features]()
  - [Starboard]()
  - [Ticketing]()
 
# 🎛️ Commands


## About user
**Version added:** 1.0.0 <br>
**Description:** Display details about a user.

**Usage:** `/about <user>` <br>
**Permissions required:** None

**Parameters:**
> user | The user to provide details about. Must be a user in the current server.

> [!NOTE]
> No personal information is provided, only information that is avaliable though either Discord's API or the user's profile page.

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*


## Points balance
**Version added:** 1.0.0 <br>
**Description:** Display the points balance of a user or the command user. <br>

**Usage:** `/balance [user]` <br>
**Permissions required:** None <br>

**Parameters:**
> **(Optional) user** | The user to display the balance of. Must be a user in the current server.

> [!TIP]
> Leaving the `user` field empty will show the command user's balance.

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Change points of a user
**Version added:** 1.0.0 <br>
**Description:** Change the points balance of a user with an active balance by a certain amount. 

**Usage:** `/change_points <user> <change>` <br>
**Permissions required:** Bot admin 

**Parameters:**
> **user** | The user to change the points balance of. Must be a user in the server.

> **change** | The amount of points to change `user`'s balance by. Must be an integer, can be positive or negative.

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Change points of all users
**Version added:** 1.0.0 <br>
**Description:** Change the points balance of all users with an active balance by a certain amount.

**Usage:** `/change_points_all <change>` <br>
**Permissions required:** Bot admin

**Parameters:**
> **change** | The amount of points to change all balances by. Must be an integer, can be positive or negative.

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Coinflip
**Version added:** 1.0.0 <br>
**Description:** Flip a coin, it can land on heads or tails.

**Usage:** `/coinflip` <br>
**Permissions required:** None 

**Parameters:** None

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Claim daily points
**Version added:** 1.0.0 <br>
**Description:** Claim 350 free points once every 24 hours.

**Usage:** `/daily` <br>
**Permissions required:** None

**Parameters:** None

> [!TIP]
> Set a reminder for every 24 hours to maximise your points!

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Help command
**Version added:** 1.0.0 <br>
**Description:** Display a list of commands

**Usage:** `/help` <br>
**Permissions required:** None

**Parameters:** None

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Mute a user
> [!NOTE]
> This command works together with the [unmute command](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#unmute-a-user)

**Version added:** 1.0.0 <br>
**Description:** Mute a user for a set period of time.

**Usage:** `/mute <user> <length> <reason>` <br>
**Permissions required:** Mute members

**Parameters:**
> **user** | A user in the current server that is not already muted.

> **length** | Time in minutes the user should be muted for.

> **reason** | The reason for muting the user.

> [!NOTE]
> If the user is already muted, this won't work!

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Pokemon collection
**Version added:** 1.0.0 <br>
**Description:** Displays your Pokemon collection.

**Usage:** `/pokemon_collection [filter]` <br>
**Permissions required:** None

**Parameters:**
> **(Optional) filter** | Filter your collection to display only Pokemon that meet certain criteria. Options: <br>
>⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀  ⠀ **• Shiny** | Filter for shiny Pokemon

> [!TIP]
> The buttons bellow your collection let you navigate between pages. The ⏩ button skips to the last page and the ⏪ button skips to the first page, use these to make searching your collection faster!

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Pokemon information
**Version added:** 1.0.0 <br>
**Description:** Displays details about a Pokemon in your collection.

**Usage:** `/pokemon_info <number>` <br>
**Permissions required:** None

**Parameters:**
> **number** | Collection number of the Pokemon in your collection. Must be an integer within your collection.

> [!IMPORTANT]
> Ensure you are using the number displayed next to the Pokemon in your collection (`/pokemon_collection`) and <ins>not</ins> the Pokemon's Pokedex number, as it will not work as intended.

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Spawn a Pokemon

> [!WARNING]
> This command is named very similarly to `/pokemon_spawns`, make sure you're looking at the right command!

**Version added:** 1.0.0 <br>
**Description:** Spawn a wild Pokemon in a certain area once every two minutes.

**Usage:** `/pokemon_spawn <area>` <br>
**Permissions required:** None

**Parameters:**
> **area** | The area in which you want to spawn a Pokemon. Each area has a different list of Pokemon that can spawn. Options: <br>
> ⠀⠀⠀⠀ **• Farfetch'd Fields** <br>
> ⠀⠀⠀⠀ **• Shaded Forest** <br>
> ⠀⠀⠀⠀ **• Cliff's Cave** <br>
> ⠀⠀⠀⠀ **• Danger Desert** <br>
> ⠀⠀⠀⠀ **• Blue Beach** <br>
> ⠀⠀⠀⠀ **• Blue Sea** <br>
> ⠀⠀⠀⠀ **• Cloudy Sky** <br>
> ⠀⠀⠀⠀ **• Mount Magma** <br>
> ⠀⠀⠀⠀ **• Dark Gravestones** <br>
> ⠀⠀⠀⠀ **• Science Lab** <br>
> ⠀⠀⠀⠀ **• Myndflike City** <br>
> ⠀⠀⠀⠀ **• Snowfield Forest** <br>
> ⠀⠀⠀⠀ **• Galactic Edge** <br>
> ⠀⠀⠀⠀ **• Event**

> [!TIP]
> Use `/pokemon_spawns` before spawning so that you can find your favourite Pokemon!

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Check the Pokemon that spawn in an area

> [!WARNING]
> This command is named very similarly to `/pokemon_spawn`, make sure you're looking at the right command!

**Version added:** 1.0.0 <br>
**Description:** Display a list of Pokemon that spawn in an area sorted by rarity.

**Usage:** `/pokemon_spawns <area>` <br>
**Permissions required:** None

**Parameters:**
> **area** | The area in which you want to check what Pokemon spawn. Each area has a different list of Pokemon that can spawn. Options: <br>
> ⠀⠀⠀⠀ **• Farfetch'd Fields** <br>
> ⠀⠀⠀⠀ **• Shaded Forest** <br>
> ⠀⠀⠀⠀ **• Cliff's Cave** <br>
> ⠀⠀⠀⠀ **• Danger Desert** <br>
> ⠀⠀⠀⠀ **• Blue Beach** <br>
> ⠀⠀⠀⠀ **• Blue Sea** <br>
> ⠀⠀⠀⠀ **• Cloudy Sky** <br>
> ⠀⠀⠀⠀ **• Mount Magma** <br>
> ⠀⠀⠀⠀ **• Dark Gravestones** <br>
> ⠀⠀⠀⠀ **• Science Lab** <br>
> ⠀⠀⠀⠀ **• Myndflike City** <br>
> ⠀⠀⠀⠀ **• Snowfield Forest** <br>
> ⠀⠀⠀⠀ **• Galactic Edge** <br>
> ⠀⠀⠀⠀ **• Event**

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Generate a random colour
**Version added:** 1.0.0 <br>
**Description:** Generate a random colour. This will provide both the colour's Hex code and RGB value. 

**Usage:** `/random_colour` <br>
**Permissions required:** None

**Parameters:** None


## Set the bot's status
**Version added:** 1.0.0 <br>
**Description:** Set the bot's status to a certain value 

**Usage:** `/set_bot_status <status_type> <text>` <br>
**Permissions required:** Bot admin

**Parameters:**
> **status_type** | The type of status. Options: <br>
> ⠀⠀⠀⠀⠀⠀⠀⠀⠀ **• Listening to** | Set status to "Listening to \<text>" <br>
> ⠀⠀⠀⠀⠀⠀⠀⠀⠀ **• Playing** | Set status to "Playing \<text>" <br>
> ⠀⠀⠀⠀⠀⠀⠀⠀⠀ **• Watching** | Set status to "Wathcing \<text>"

> **text** | Text to show in status. Example: `Playing <text>`

> [!NOTE]
> Due to how Discord handles the status of bots, they are limited to these options.

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Set channel slowmode
**Version added:** 1.0.0 <br>
**Description:** Set the current channel's slowmode

**Usage:** `/set_slowmode <cooldown>` <br>
**Permissions required:** Manage messages

**Parameters:**
> **cooldown** | Time in seconds to set the channel's slowmode to

> [!TIP]
> This isn't limited to Discord's channel setting options! You can use this to set the slowmode to anywhere from 1-21600 seconds! (Max 6 hours)

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Search for a song on Spotify
**Version added:** 1.0.0 <br>
**Description:** Searches Spotify fro a prompt and returns the top song

**Usage:** `/spotify_search` <br>
**Permissions required:** None

**Parameters:**
> **search** | Search spotify for this term

> [!NOTE]
> This will only return the top <ins>song</ins> - albums, artists, etc. will not be returned.

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Staff help command
**Version added:** 1.0.0 <br>
**Description:** Display a list of commands for server staff and bot admins

**Usage:** `/staff_help` <br>
**Permissions required:** None

**Parameters:** None

> [!IMPORTANT]
> While anyone can use this command, the commands listed require certain permissions

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Add a user to a ticket
**Version added:** 1.0.0 <br>
**Description:** Adds a user to the current ticket

**Usage:** `/ticket_add <user>` <br>
**Permissions required:** None, but must be in a ticket

**Parameters:**
> **user** | The user to add to the current ticket. Must be a user that is in the server but not already in the current ticket

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Close a ticket
**Version added:** 1.0.0 <br>
**Description:** Close the currently open ticket.

**Usage:** `/ticket_close` <br>
**Permissions required:** None, but must be in a ticket

**Parameters:** None

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Create ticket GUI
**Version added:** 1.0.0 <br>
**Description:** Send the 'open a ticket' GUI to the current channel.

**Usage:** `/ticket_create_gui` <br>
**Permissions required:** Manage Server

**Parameters:** None

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Ticket remove
**Version added:** 1.0.0 <br>
**Description:** Remove a user from the current ticket.

**Usage:** `/ticket_remove <user>` <br>
**Permissions required:** Kick members, and must be in a ticket

**Parameters:**
> **user** | The user to remove from the current ticket. Must be a member in the server who is already in the ticket.

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Unmute a user
> [!NOTE]
> This command works together with the [mute command](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#mute-a-user)

**Version added:** 1.0.0 <br>
**Description:** Unmute a muted user

**Usage:** `/unmute <user> <reason>` <br>
**Permissions required:** Mute members

**Parameters:**
> **user** | User to be unmuted. Must be a member of the server that is currently muted

> **reason** | Reason for unmuting the user

> [!NOTE]
> If the user isn't muted, this won't work!

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*



## Work for points
**Version added:** 1.0.0 <br>
**Description:** Go to 'work', return in two hours to claim 80-120 points.

**Usage:** `/work` <br>
**Permissions required:** None

**Parameters:** None

> [!TIP]
> If you use this more than three times in a day, you can earn more than you would with `/daily` every day!

*[Return to Table of Contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#-table-of-contents)*


# ⭐ features

## Starboard

**Version added:** 1.0.0 <br>
**Description:** When a message recieves three or more ⭐ reactions, it will be sent to the starboard channel

**Usage:** React to a cool message with the ⭐ emoji, once 3 people react with that, it will be sent to the starboard! <br>
**Permissions required:** Add reactions

> [!IMPORTANT]
> If the bot goes offline for any reason, any messages sent before the bot comes back online that reach 3 ⭐ reactions <ins>will not</ins> be starboarded. This is because the messages are not in the bot's cache, and as such are essentially invisible to it. If this happens, please ask server staff to send the message manually to the staboard channel.



## Ticketing

**Version added:** 1.0.0
**Description:** Users can open a private channel with staff to discuss issues or questions.

**Usage:** Users simply click the 'open ticket' button in the designated ticket support channel. They will then get a private channel to talk to staff through. <br>
**Permissions:** None