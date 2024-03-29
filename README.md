# PreBot

PreBot is a Discord Bot Software made in java, PreBot alone does nothing,
but you add your features by using plugins! plugins design are similar to bukkit, with most things simplified to you!

# NOTE:

This project is still in alpha, if you have any suggestions feel free to open a feature request on this GitHub!

# Installation

## On Windows

1. Create a new folder wherever on your computer, this is where you will place prebot.
2. Download the latest release from [Releases](https://github.com/BlueTree242/PreBot/releases/), or experimental
   development build from [Jenkins](https://github.com/BlueTree242/PreBot/releases/)
   Download the `PreBot-VERSION.jar`, and rename to `prebot.jar`
3. Download [Run Script](installation/run_windows.bat) (view as raw and save page as)
4. Start the bot by double-clicking the start script, the configuration will be generated. Configure your token
   in `config.yml`
5. Put your plugins in the plugins folder
6. Start the bot again, it should go online.

Your bot will stay online as soon as the bot's terminal is on and running, and your machine does not shut down or sleep/hibernate

## On Linux

Currently, documenting only pterodactyl panel installation

### Pterodactyl Panel Installation

1. Create a new server, use this [egg](installation/egg-prebot.json) (view as raw and save page as)
**If you are not an admin on panel**, you can use the regular java start command (the same one for minecraft, but bot.jar instead of server.jar),
in case of minecraft egg, just set your server jarfile to `bot.jar`
2. Download the latest release from [Releases](https://github.com/BlueTree242/PreBot/releases/), or experimental
   development build from [Jenkins](https://github.com/BlueTree242/PreBot/releases/)
   Download the `PreBot-VERSION.jar`, and rename to `prebot.jar`, and upload to your server.
3. Start your server, you can configure your bot in config.yml
4. Put your plugins in plugins folder
5. Start the bot again, it should go online

# Building From Source

Use the following command to build PreBot from the source:

```bash
./gradlew build
```

Then you should find the standalone launcher in `launcher\build\libs`.

# Making a PreBot Plugin

See the Instructions for making a PreBot Plugin [here](MAKING_PLUGIN.md)

# TODO

-  [X] Discord Commands API.
-  [ ] Messages System, and Placeholder system for plugins.
-  [ ] Database for plugins, to ease for database-based plugins.
-  [ ] Settings & Configuration (Per Guild) with powerful API.
-  [ ] Library System, make prebot download libraries instead of shading them.
-  [ ] Ability to run the bot as a Spigot, Bungee or Velocity plugin.