# 📋 SafeBot Documentation

<br>

# 📖 Table of contents
- Commands
  - [About](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#about-user)
  - [Balance](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/SafeBot/docs.md#points-balance)
  - Change points
  - Change points (all)
  - Coinflip
  - Daily
  - Help
  - Mute
  - Pokemon
    - Collection
    - Info
    - Spawn
    - Spawns
  - Random colour
  - Set bot status
  - Set slowmode
  - Spotify search
  - Staff help
  - Tickets
    - Add
    - Close
    - Create GUI
    - Remove
  - Unmute
- Features
  - Starboard
  - Ticketing
 
# 🎛️ Commands

## About user
**Version added:** 1.0.0 <br>
**Description:** Display details about a user.

**Usage:** `/about <user>` <br>
**Permissions required:** None

**Parameters:**
> **user** | The user to provide details about. Must be a user in the current server.


## Points balance
**Version added:** 1.0.0 <br>
**Description:** Display the points balance of a user or the command user. <br>

**Usage:** `/balance [user]` <br>
**Permissions required:** None <br>

**Parameters:**
> **(Optional) user** | The user to display the balance of. Must be a user in the current server. If left blank the command will display the command user's balance. 


## Change points of a user
**Version added:** 1.0.0 <br>
**Description:** Change the points balance of a user with an active balance by a certain amount. 

**Usage:** `/change_points <user> <change>` <br>
**Permissions required:** Bot admin 

**Parameters:**
> **user** | The user to change the points balance of. Must be a user in the server.

> **change** | The amount of points to change `user`'s balance by. Must be an integer, can be positive or negative.


## Change points of all users
**Version added:** 1.0.0 <br>
**Description:** Change the points balance of all users with an active balance by a certain amount.

**Usage:** `/change_points_all <change>` <br>
**Permissions required:** Bot admin

**Parameters:**
> **change** | The amount of points to change all balances by. Must be an integer, can be positive or negative.


## Coinflip
**Version added:** 1.0.0 <br>
**Description:** Flip a coin, it can land on heads or tails.

**Usage:** `/coinflip` <br>
**Permissions required:** None 

**Parameters:** None


## Claim daily points
**Version added:** 1.0.0 <br>
**Description:** Claim 350 free points once every 24 hours.

**Usage:** `/daily` <br>
**Permissions required:** None

**Parameters:** None


## Help command
**Version added:** 1.0.0 <br>
**Description:** Display a list of commands

**Usage:** `/help` <br>
**Permissions required:** None

**Parameters:** None


## Mute a user
**Version added:** 1.0.0 <br>
**Description:** Mute a user for a set period of time.

**Usage:** `/mute <user> <length> <reason>` <br>
**Permissions required:** Mute members

**Parameters:**
> **user** | A user in the current server that is not already muted.

> **length** | Time in minutes the user should be muted for.

> **reason** | The reason for muting the user.


## Pokemon collection
**Version added:** 1.0.0 <br>
**Description:** Displays your Pokemon collection.

**Usage:** `/pokemon_collection [filter]` <br>
**Permissions required:** None

**Parameters:**
> **filter** | Filter your collection display only Pokemon that meet certain criteria. Options: <br>
>⠀⠀⠀ ⠀ **• Shiny** | Filter for shiny Pokemon


## Pokemon information
**Version added:** 1.0.0 <br>
**Description:** Displays details about a Pokemon in your collection.

**Usage:** `/pokemon_info <number>` <br>
**Permissions required:** None

**Parameters:**
> **number** | Collection number of the Pokemon in your collection. Must be an integer within your collection.


## Spawn a Pokemon
**Version added:** 1.0.0 <br>
**Description:** Spawn a wild Pokemon in a certain area once every two minutes.

> [!WARNING]
> This command is named very similarly to `/pokemon_spawns`, make sure you're looking at the right command!

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


## Check the Pokemon that spawn in an area
**Version added:** 1.0.0 <br>
**Description:** Display a list of Pokemon that spawn in an area sorted by rarity.

> [!WARNING]
> This command is named very similarly to `/pokemon_spawn`, make sure you're looking at the right command!

**Usage:** `/pokemon_spawns <area>` <br>
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


## Command
**Version added:** 1.0.0 <br>
**Description:** 

**Usage:** `/` <br>
**Permissions required:** 

**Parameters:**
> **a** | z

> **b** | y


















