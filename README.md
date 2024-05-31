# Vanilla Essentials Config
A modified config for the plugin <a href="https://github.com/EssentialsX/Essentials" target="_blank">EssentialsX</a> that removes its undesirable replacements of vanilla features and makes the plugin act more "vanilla-like."<br>
e.g. not being able to use selectors(<code>@s</code>, <code>@a</code>, <code>@e</code>, etc.) with <code>/kill</code> because their replacement command doesn't support them(despite not adding any new features that the vanilla command doesn't already have.)<br>

or the <code>/ping</code> command which just replies back to you in the chat with "pong" while overriding actually useful commands that allow you to see your ping.

## Changes
1. Disables the EssentialsX version of the following commands, and their aliases, and uses the vanilla ones.
   - /kill
   - /teleport
   - /message
   - /whisper
   - /clear
   - /ban
   - /kick
   - /enchant
   - /xp
   - /gamemode
   - /weather
   - /ping
2. Disables the **enabled by default** "easter egg" that turns mobs into their baby variety when right clicked with a milk bucket by any player.
3. Makes the /heal command not remove potion effects(including positive effects for some reason) when ran.
4. Makes you drop items on the floor when given more with a full inventory instead of just deleting them.
5. Sets the default stack size to 1 instead of the maximum.

<b>EssentialsX does not have a config option to prevent it from forcing operators to fly when joining in so-called "unsafe" areas.</b>
<br>
<b>You will need to set the <code>essentials.fly.safelogin</code> permission to false with a plugin like</b> <a href="https://luckperms.net/download" target="_blank">Luckperms</a>
