## Table of contents
- [Contact & about me](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/README.md#contact--about-me)
- [Projects](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/README.md#projects)
  - [JoyBot (Python)](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/README.md#joybot-python)
  - [SafeBot (Python)](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/README.md#safebot-python)


## Contact & about me
- My [Discord](https://discord.com/users/524064761525305344)
- My Discord server (coming soon)
- My [Pronouns.page](https://en.pronouns.page/@hi.joy)

## Projects
### JoyBot (Python)
- JoyBot was my first large Discord bot, containing:
  - Legacy text-based commands
  - A spawn and collection system
    - Users spawn and collect a variety of over 200 unique spawns
    - Users can race to find 'Challenge Spawns' - a randomly selected spawn that 
  - A truth or dare game
  - A fun fact command
  - A fishing command
  - A "who is most likely to" question command
  - A channel slowmode adjustment command 
- JoyBot is hosted on my Raspberry Pi, and is currently used actively in a private server of nearly 50 members with frequent updates
- JoyBot is made with [discord.py](https://discordpy.readthedocs.io/en/stable/)

### SafeBot (Python)
- SafeBot is my first attempt to make a complete multipurpose slash command-based Discord bot, and is far more advanced than JoyBot, containing:
  - A complete slash command and embed system
  - Error handling for all commands with developer logs for unexpected errors
  - A currency system
    - Users can earn and spend a currency from a balance stored in an external file
    - (Work in progress) Store and purchasing system with real-time store updates, with all store information managed with an external JSON file 
  - A complete ticketing system
    - Users can create a private channel with staff, and are able to add extra users into the ticket
  - Pokémon collecting game
    - Every 2 minutes, users can spawn a random Pokémon
      - Pokémon are spawned based on the area the user selected, and the rarity of the Pokémon
      - All Pokémon have a small chance to be [shiny](https://bulbapedia.bulbagarden.net/wiki/Shiny_Pok%C3%A9mon), which is influenced by their rarity; with rarer Pokémon having a higher chance to be shiny 
  - An about user command
    - Gets and displays data about a provided user from the Discord API
  - A Spotify search command
    - Searches Spotify's API for a term and provides details about the top result 
  - Moderation commands
    - Mute, unmute, and slowmode control commands
- Safebot's commands: Public
  - `/about <user>` : Provides details about a Discord user from Discord's API
  - `/balance [user]` : View your balance or another user's balance
  - `/buy <itemID>` : (Work in progress) Purchases an item from the store and adds it to your inventory
  - `/coinflip` : FLip a coin, it can land on heads or tails
  - `/daily` : Collect free points once every 24 hours
  - `/help` : Provides a list of commands and their uses
  - `/pokemon_collection` : (Work in progress) Displays a list of every Pokémon a user has caught
  - `/pokemon_spawn <area>` : Spawns a random Pokémon from `area`'s spawn pool
  - `/pokemon_spawns <area>` : Shows a list of all Pokémon that can be found in `area` and their rarity 
  - `/spotify_search <search>` : Searches the SPotify API for `search` and provides information about the top result
  - `/store` : (Work in progress) Displays the current store, with the ID, name, and price of each item
  - `/ticket_add <user>` : Adds `user` to the current ticket if not already in it
  - `/ticket_close` : Asks the user for confirmation, then closes the current ticket
  - `/work` : Use this and wait 2 hours to claim extra free points
- SafeBot's commands: Server moderation
  - `/mute <user> <length> <reason>` : Mutes `user` for `length` minutes with the reason `reason`
  - `/staff_help` : Provides a list of moderation and management commands
  - `/starboard_info` : Provides details about the starboard feature
  - `/ticket_create_gui` : Sends the create ticket embed and button to the current channel
  - `/ticket_remove <user>` : Removes `user` from the current ticket
  - `/unmute <user> <reason>` : Unmutes `user` if muted, with reason `reason`
- SafeBot's commands: Bot management
  - `/change_points <user> <change>` : Changes `user`'s points balance by `change`
  - `/change_points_all <change>` : Changes all user's points balance by `change`
  - `/set_bot_status <status_type> <text>` : Changes the bot's presence to `status_type` `text`
- SafeBot is still being developed, and will be hosted on my Raspberry Pi for use in my public Discord server
- SafeBot is made with [discord.py](https://discordpy.readthedocs.io/en/stable/)


[Return to table of contents](https://github.com/hi-joy-nz/hi-joy-nz/blob/main/README.md#table-of-contents)
