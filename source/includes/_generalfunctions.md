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
