# Anvil
Open the anvil gui anywhere!

## Commands and Permissions
- /anvil - (Permission: `anvil.open`) Opens the anvil gui from anywhere!
- /anvil reload - (Permission: `anvil.admin`) Reloads the config files

## Config.yml
```yaml
#This determines whether a sound is played when the command /anvil is run and
#the gui is opened
#Possible values: [true, false],
# true - a sound will be played
# false - a sound will not be played
playSound: true

#This determines the sound that is played (if the above setting is set to true)
#Find the list of sounds for your minecraft version.
#For 1.16.5, this is the list: https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Sound.html
soundName: "ENTITY_ENDERMAN_TELEPORT"
    
#This is the message sent to the console when the command /anvil is executed
#Set the message to "none" to disable.
#Color codes and unicode characters work, but might glitch.
onConsoleExecuteCommand: "This command cannot be executed from the console!"

#This is the message sent to a player who does not have the permission to
#execute the command /anvil
#Set the message to "none" to disable.
#Color codes and unicode characters work, but might glitch.
noPermission: "Unknown command. Type \"help\" for help."

#This sets the title of the GUI (only works in 1.14+)
#Color codes and unicode characters work, but might glitch.
title: "&6Repair & Name"
```
