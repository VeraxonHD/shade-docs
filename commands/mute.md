### Mute

Adds a mute role to a user, which MUST be set up prior, for a certain amount of time.

| **Usage** | **Permissions** | **Description/Information** |
| :--- | :--- | :--- |
| !!mute \[user\] \[time\] \[reason\] | MANAGE\_MESSAGES | \[time\] requires a value and a unit e.g    "5m", "7h", "1d" |
| !!unmute \[user\] | MANAGE\_MESSAGES | Removes a user's mute role. |

> **N.B A MUTE ROLE MUST BE CREATED PRIOR.**
>
> If your Mute role is not named "Muted" \(no quotemarks\), you must change it in the config. [See here for how to do that](/configure/convars.md).
>
> If there is no such role at the time of mute, the mute will not go through the system.



