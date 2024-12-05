<link href="style.css" rel="stylesheet">
<link rel="shortcut icon" type="image/x-icon" href="../favicon.ico">
<title>SafeBot | Updates</title>

# SafeBot Updates


## SafeBot Version 1.2.0 Release Notes
6th of December, 2024 • Joy

### New commands
List of tone tags
- Usage `/tonetags`
- Get a list of common tone tags and their meaning.

Pokémon quests
- Usage `/pokemon_quests`
- View quests and claim those you have completed.

### New Pokémon feature: Quests
Complete quests to earn epic rewards!

- Check your progress on quests and claim any rewards with `/pokemon_quests`
- Earn rewards, such as points and exclusive Pokémon!

This feature also introduces Lickitung for the first time, which is a quest exclusive Pokémon!

### Adjustments
- Added the "user type" field to the about user command
- Changed the "account created" and "joined server" fields in the about user command to show relative times
- Added the time passed since a user joined the server or created their account in the about user command
- Added a sticker count and emoji count field to the about server command

### Spawn changes
- Completely updated what Pokémon spawn in every Spawn Area
- New Pokémon debuts: Lickitung (quests), Doduo, Dodrio, Golem, Victreebel, and one other..?
- Check the new spawns with `/pokemon_spawn`!

### Bug fixes
- Fixed an issue where the display name/nickname field of the about user command would show the user's username instead of their display name if the user didn't have a nickname
- Fixed an issue where the list of a user's roles was reversed in the about user command



## SafeBot Version 1.1.2 Release Notes
26th of November, 2024 • Joy

### New command: Ask the magic 8ball!
Usage: `/8ball <question>`
- Ask the magic 8ball a question and get an answer!

### New spawn type: Marked Pokémon!
- Marked Pokémon are a new, super rare type of spawn!
    - Every Pokémon has a 1/1500 chance to be marked.
    - Marked Pokémon are indicated by a 🎖️ in your collection and in the spawn footer.
- You can also filter your collection for marked Pokémon.

### Spawn changes
- Tentacool, Shellder, Squirtle, Tentacruel, and Cloyster no longer spawn at Blue Beach.
- (DEBUT!) Dragonair can now be found super rarely in the Blue Sea.
- (DEBUT!) Arbok can now be found near the Dark Gravestones.


## SafeBot Verison 1.1.1 Release Notes
20th of November, 2024 • Joy

### Adjustments
- Increased the shiny rates of spawns
    - Common: 1/450 -> 1/550
    - Uncommon: 1/400 -> 1/500
    - Rare: 1/350 -> 1/450
    - Very rare: 1/250 -> 1/350
    - Super rare: 1/150 -> 1/250
    - Legendary and Mythical shiny rates have not changed

### New "Hitmon Gym" Spawn Area
- This spawn area has a focus on fighting-type Pokémon, here you can find:
    - Mankey
    - Machop
    - Poliwhirl
    - Primape
    - Machoke
    - Hitmonlee
    - Hitmonchan
    - Poliwrath
    - Machamp (DEBUT!)
    - Tauros (DEBUT!)

### Spawn changes
- Exeggutor no longer spawns in the Farfetch'd Fields Spawn Area
- Beedrill can now be found rarely in the Cloudy Sky Spawn Area
- Pidgeot can now be found more commonly in the Cloudy Sky Spawn Area
- (DEBUT!) Dragonite is now a super rare spawn in the Cloudy Sky Spawn Area
- Ninetales can now be found very rarely in the Dark Gravestones Spawn Area
- Growlithe, Mankey, Primape, Hitmonlee, and Hitmonchan can no longer be found in the Myndflike City Spawn Area
- Goldeen can now be commonly found in the Snowfield Forest Spawn Area
- Staryu can now be found uncommonly in the Snowfield Forest Spawn Area
- Horsea and Seaking can now rarely be found in the Snowfield Forest Spawn Area
- Omanyte and Kabuto can now be found very rarely in the Science Lab Spawn Area

### New spawn event
- Visit the [news page](https://hi-joy-nz.github.io/SafeBot/News) to learn about SafeBot's next spawn event!

### Bug fixes
- Fixed an issue where if `/spotify_search` couldn't find any results it would send an error.
- Fixed a typo in Ninetales' name.
  

## SafeBot Version 1.1.0-3 Release Notes
18th of November, 2024 • Joy

### Adjustments
- Updated the "command on cooldown" message for commands that have a cooldown to now display a live-updating timer with the time until you can use it again.


## SafeBot Version 1.1.0-2 Release Notes
17th of November, 2024 • Joy

### Adjustments
- Updated the `/store` store.

### Bug fixes
- Fixed an issue where typos in the store would cause errors when purchasing specific Pokémon.


## SafeBot Version 1.1.0-1 Release Notes
16th of November, 2024 • Joy

### Bug fixes
- Fixed an issue where certain legendary and mythical Pokémon wouldn't show in user's collections when using the legendary filter.


## SafeBot Version 1.1.0 Release Notes
15th of November, 2024 • Joy
### Changes to starboard message
- Changed the emoji before the message jump link from ✨ to ⭐
- If a message has more than one attachment, the message will now show this.
- If the attachment of a starboarded message can not be displayed, it will say this.

### Changes to suggestion command
- Renamed the command from `/suggest` to `/feedback`
- Added the "type" parameter, which is used to describe the nature of your feedback.
- [Read the docs](https://hi-joy-nz.github.io/SafeBot/Docs#provide-feedback) for more details

### New about server command
- Similar to `/about`, but instead it provides details about the current server as opposed to a user.
- [Read the docs](https://hi-joy-nz.github.io/SafeBot/Docs#about-a-server) for more details

### Spawn changes
- Exeggcute no longer spawns in the Galactic Edge spawn area
- Bulbasaur, Pikachu, Ekans, and Tangela no longer spawn in the Farfetch'd Field spawn area
- Changed Seel from being a common spawn to being an uncommon spawn in the Blue Sea spawn area
- Poliwrath makes its debut as a super rare spawn in the Blue Sea spawn area
- Eevee makes its debut as a rare spawn in the Science Lab spawn area

### Bug fixes
- Fixed an issue where the legendary/mythical filter wouldn't be usable (`/Pokémon_collection`)
<br>

## SafeBot Version 1.0.1-1 Release Notes
13th of November, 2024 • Joy
### Adjustments
- Starboard message footers now show the time the original message was sent, as opposed to the time it was starboarded.
- Starboard message slightly altered.

### Bug fixes
- When spawning a Pokémon in the Event Spawn Area, there is no longer a chance you recieve an error message.


## SafeBot Version 1.0.1 Release Notes
12th of November, 2024 • Joy
### New & updated features
- Added legendary/mythical filter to `/Pokémon_collection`, so that you can filter your collection for your rarest Pokémon!
- Starboard now supports images and will show the *first image attached* to a starboarded message.
- `/work` will now auto-restart work after you claim it
- `/Pokémon_info` now displays how many of that Pokémon you have caught. Thanks to `@eiranroan` for this suggestion!

### Spawn changes
- Enabled the Event spawn area: Discover the ancient world with the Fossilised Fortunes event spawns! If you're feeling lucky, shiny Pokémon are more likely to be found in the event area! [Read more about this event](https://hi-joy-nz.github.io/SafeBot/News#spawn-event-fossilised-fortunes).
- Jigglypuff no longer spawns in the Science Lab area, and Abra is now commonly found there instead!

### Bug fixes
- `/work` cooldown is now per-user, and not a global cooldown
- Other users are no longer able to use the page contol buttons on your `/Pokémon_collection`
- The join "RAWR" will now only be triggered if the server joined is the Safe Haven server.


## SafeBot Version 1.0.0 Release Notes
9th of November, 2024 • Joy
### SafeBot's public release
SafeBot is now avaliable for public use in the [Safe Haven Discord server](https://discord.gg/BcuRXcBasz)
