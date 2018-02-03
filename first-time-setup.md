# First Time setup! Welcome to Shade!

Hi, and thanks for adding Shade to your guild! What follows will act as your guide for setting up Shade to your liking, as well as instructing you on what to do first.

Part one: Configuration

Configuring Shade is the key part to enabling any functionality. The following are steps you should take to ensure Shade is fully functional.

1. Set a designated log channel. This can be done by typing `!!configure logchannelID <a channel id>`.

   1. Until this step is completed, you will not be able to access any of Shade's commands, log functions or statistical information.

2. If you want, you can also set other log channels for specific commands: N.B if not set, they will all go to the log channel you set up in part \(1\)

   1. Using `!!configure`...

      1. `!!configure modlogchannelID <channel id>` will send all moderation log messages to that channel.

      2. `!!configure voicelogchannelID <channel id>` will send all voice channel join/leave logs to that channel.

      3. `!!configure joinlogchannelID <channel id>` will send all join/leave logs to that channel.

3. Change which commands, events and AutoMod[^1] features you can and cannot use.

   1. By default, all commands are enabled. However, you can disable any of the commands by using the command `!!configure disabledCommands <command name in lower case>`

   2. You can replace "disabledCommands" with either "disabledEvents", "disabledMisc" or "disabledAutoMod" to achieve similar goals. **More information can be found in the next page of this book.**

      1. N.B AutoMod is currently in development. Changing this convar \(config variable\) will not do anything just yet.

4. If you want Shade to put messages when people join and leave:

   1. Make sure "disabledMisc" does not contain the word "memberLog" \(no quotemarks\).

      1. If it does, delete it from the list.

   2. Type `!!configure joinLogChannel <channel id>`. 

      1. Note the difference between the convars "joinLogChannelID" \(the mod-only log channel where user data is sent\) and "joinLogChannel" \(The channel where the usual "welcome to the server" message is sent\).

5. **You're done with the mandatory settings!**

   1. If you need to configure Shade more, check out the next page.



[^1]: AutoMod is currently in development. 

