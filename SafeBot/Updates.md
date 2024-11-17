<link href="style.css" rel="stylesheet">
<link rel="shortcut icon" type="image/x-icon" href="favicon.ico">

# SafeBot Updates

## SafeBot Version 1.1.0-2 Release Notes
17th of November, 2024 • Joy

### Adjustments
- Updated the `/store` store.

### Bug fixes
- Fixed an issue where typos in the store would cause errors when purchasing specific Pokemon.


## SafeBot Version 1.1.0-1 Release Notes
16th of November, 2024 • Joy

### Bug fixes
- Fixed an issue where certain legendary and mythical Pokemon wouldn't show in user's collections when using the legendary filter.


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
- Fixed an issue where the legendary/mythical filter wouldn't be usable (`/pokemon_collection`)
<br>

## SafeBot Version 1.0.1-1 Release Notes
13th of November, 2024 • Joy
### Adjustments
- Starboard message footers now show the time the original message was sent, as opposed to the time it was starboarded.
- Starboard message slightly altered.

### Bug fixes
- When spawning a Pokemon in the Event Spawn Area, there is no longer a chance you recieve an error message.


## SafeBot Version 1.0.1 Release Notes
12th of November, 2024 • Joy
### New & updated features
- Added legendary/mythical filter to `/pokemon_collection`, so that you can filter your collection for your rarest Pokemon!
- Starboard now supports images and will show the *first image attached* to a starboarded message.
- `/work` will now auto-restart work after you claim it
- `/pokemon_info` now displays how many of that Pokemon you have caught. Thanks to `@eiranroan` for this suggestion!

### Spawn changes
- Enabled the Event spawn area: Discover the ancient world with the Fossilised Fortunes event spawns! If you're feeling lucky, shiny Pokemon are more likely to be found in the event area! [Read more about this event](https://hi-joy-nz.github.io/SafeBot/News#spawn-event-fossilised-fortunes).
- Jigglypuff no longer spawns in the Science Lab area, and Abra is now commonly found there instead!

### Bug fixes
- `/work` cooldown is now per-user, and not a global cooldown
- Other users are no longer able to use the page contol buttons on your `/pokemon_collection`
- The join "RAWR" will now only be triggered if the server joined is the Safe Haven server.


## SafeBot Version 1.0.0 Release Notes
9th of November, 2024 • Joy
### SafeBot's public release
SafeBot is now avaliable for public use in the [Safe Haven Discord server](https://discord.gg/BcuRXcBasz)
