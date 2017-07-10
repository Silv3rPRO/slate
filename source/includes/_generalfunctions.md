# General functions

## Log

```lua
function log(message)

log("Hello! This is a message.")
log("I have " .. getTeamSize() .. " pokémon in my team.")
```

Writes the specified message to the message log.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
message   | string | Message to display

## Fatal

```lua
function fatal(message)

fatal("You are not on the correct map, stopping the script!")
```

Writes the specified message to the message log and stops the bot.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
message   | string | Message to display

## Logout

```lua
function logout(message)
```

Displays the specified message to the message log and logs out.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
message   | string | Message to display

## StringContains

```lua
function stringContains(haystack, needle)
```

Returns true if the haystack contains the specified needle, ignoring the case.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
haystack  | string | String to analyze
needle    | string | String to search in the haystack

## PlaySound

```lua
function playSound(file)
```

Returns playing a custom sound.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
file      | string | Sound file to play

## RegisterHook

```lua
function registerHook(eventName, callback)

function sendBattleCry()
  log("FOR THE HORDE!")
end

registerHook("onBattleAction", sendBattleCry())
```

Calls the specified function when the specified event occurs.

### PARAMETERS

Parameter | Type     | Description
--------- | -------- | -----------
eventName | string   | Event that triggers the specified callback function
callback  | function | Function to call when the specified event occurs
