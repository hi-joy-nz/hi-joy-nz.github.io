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
  - A spawn and collection system, where users spawn and collect a variety of over 200 unique spawns <br>
  ![Detailed collection command](https://cdn.discordapp.com/attachments/1220996839252430911/1297323656841531495/image.png?ex=6715824e&is=671430ce&hm=4cffd56cc1fa6e539a959452dceae5b4b50801c6d31bcd55750a1107249bd4d6&)
  - A truth or dare game
  - A fun fact command
  - A fishing command
  - A "who is most likely to" question command
  - A channel slowmode adjustment command <br>
  ![Slowmode change command](https://cdn.discordapp.com/attachments/1220996839252430911/1297325126584500315/image.png?ex=671583ad&is=6714322d&hm=5d7bacd7bcff744fe9287b1c5e1ef4dc9a12bc4783850989352a17e04c9ef92b&)
- JoyBot is hosted on my Raspberry Pi, and is currently used actively in a private server of nearly 50 members with frequent updates
- JoyBot is made with [discord.py](https://discordpy.readthedocs.io/en/stable/)

### SafeBot (Python)
- SafeBot is my first attempt to make a complete multipurpose slash command-based Discord bot, and is far more advanced than JoyBot, containing:
  - A complete slash command and embed system
  - Error handling for all commands with developer logs for unexpected errors
  - A currency system
    - Users can earn and spend a currency from a balance stored in an external file
    - (Work in progress) Store and purchasing system with real-time store updates, with all store information managed with an external JSON file <br>
    ![Balance command](https://cdn.discordapp.com/attachments/1220996839252430911/1297325919345574040/image.png?ex=6715846a&is=671432ea&hm=45711b131c568a4a03cfb9c7893383c4dcd78bf6f326c4954c8a067e2762f2e2&) <br>
    ![Daily command](https://cdn.discordapp.com/attachments/1220996839252430911/1297327283450806365/image.png?ex=671585af&is=6714342f&hm=66d470235c4435575b98f125190b303853100c4286ff2ca088cf6b7738182f9d&)
  - A complete ticketing system
    - Users can create a private channel with staff, and are able to add extra users into the ticket <br>
    ![Open ticket button](https://cdn.discordapp.com/attachments/1220996839252430911/1297326157846544404/image.png?ex=671584a3&is=67143323&hm=d375941856cd19e75a55cc8e7aeaf5e1de00ced222a233ef13e90ea6a5a91c1c&)
  - An about user command
    - Gets and displays data about a provided user from the Discord API
    ![About command](https://cdn.discordapp.com/attachments/1220996839252430911/1297326703722627072/image.png?ex=67158525&is=671433a5&hm=9a216dd4f2fb53e05ec1e96b45afd281bad45a11f3e9d56397517e2cea591924&)
  - A Spotify search command
    - Searches Spotify's API for a term and provides details about the top result <br>
    ![Spotify search command](https://media.discordapp.net/attachments/1220996839252430911/1297323033207509134/image.png?ex=671581ba&is=6714303a&hm=f0b4bfb7eff373ee7c21db58d7ca8c0fab82aa0bbe9b8fb211617a9b9ab447ca&)
  - Moderation commands
    - Mute, unmute, and slowmode control commands
- Safebot's commands: Public
  - `/about <user>` : Provides details about a Discord user from Discord's API
  - `/balance [user]` : View your balance or another user's balance
  - `/buy <itemID>` : (Work in progress) Purchases an item from the store and adds it to your inventory
  - `/coinflip` : FLip a coin, it can land on heads or tails
  - `/daily` : Collect free points once every 24 hours
  - `/help` : Provides a list of commands and their uses
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
