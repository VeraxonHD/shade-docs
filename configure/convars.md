### List of convars

| **Convar title** | **What it does** | **Possible values** |
| :--- | :--- | :--- |
| disabledCommands | Any command name \(lower case\) in this field will be disabled on the server. | Any command name, separated with a space. |
| disabledEvents | Any event names here will be disabled. | No events currently use this convar. See disabledMisc |
| disabledMisc | Any values here will disable certain options | memberLog, voiceLog, messageLog |
| disabledAutoMod | Any values here will disable automod features. | This is currently not operational. |
| logChannelID | The "main" log channel ID | A snowflake \(Channel ID\) |
| modlogChannelID | The secondary log channel for all moderative commands | Ditto. |
| voiceLogChannelID | The secondary log channel for all voice logging embeds. | Ditto. |
| autoCleanUpBlacklist | commands here will not be automatically deleted. | AutoCleanup is globally disabled currently due to a bug. |
| muteRoleName | The role name of the muted role. | Default value = "Muted". |
| selfRoles | Roles here can be applied to any user. | The name of any role, separated by spaces. |
| joinLogChannel | The channel to which the "Welcome/Goodbye &lt;user&gt;" message will send | Snowflake \(channel ID\) |



