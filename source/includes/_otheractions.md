# Other actions

## PushDialogAnswer

```lua
function pushDialogAnswer(answerIndex)

pushDialogAnswer(2)
pushDialogAnswer(1)
pushDialogAnswer(3)
talkToNpc("Jackson") -- Will select 2, 1 then 3.
```

Adds the specified answer to the answer queue. It will be used in the next dialog.

This function should be called before a `talkToNpc` or `talkToNpcOnCell`.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
answerIndex | number | Index of the answer or index of the pokémon to select

## UseItem

```lua
function useItem(itemName)

useItem("Bicycle")
useItem("Escape Rope")
```

Uses the specified item.

This function is usable in the field and in battle.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
itemName    | string | Name of the item (case insensitive)

## UseItemOnPokemon

```lua
function useItemOnPokemon(itemName, pokemonIndex)

useItemOnPokemon("Potion", 1)
useItemOnPokemon("Rare Candy", 5)
```

Uses the specified item on the specified pokémon.

This function is usable in the field and in battle.

### PARAMETERS

Parameter    | Type   | Description
-----------  | ------ | -----------
itemName     | string | Name of the item (case insensitive)
pokemonIndex | number | Index of the pokémon (1-6)

## ForgetMove

```lua
function forgetMove(moveName)

forgetMove("Dragon Rage")
```

Only usable when learning a move, inside `onMoveLearning`.

Forgets the specified move, if existing, in order to learn a new one.

### PARAMETERS

Parameter    | Type   | Description
-----------  | ------ | -----------
moveName     | string | Name of the move (case insensitive)

## ForgetAnyMoveExcept

```lua
function forgetAnyMoveExcept(moveNames)

forgetAnyMoveExcept({"Fly", "Cut", "Psychic", "Thunder"})
```

Only usable when learning a move, inside `onMoveLearning`.

Forgets the first move that is not one of the specified moves.

### PARAMETERS

Parameter | Type            | Description
--------- | --------------- | -----------
moveNames | array of string | Name of the moves (case insensitive)

## SetOption

```lua
function setOption(index, value)
```

Sets the option at a particular index, or creates it if it doesn't exist.

This function only affects the PROShine client user interface.

### PARAMETERS

Parameter | Type    | Description
--------- | ------- | -----------
index     | number  | Index of the option.
value     | boolean | Value of the option (true/false).

## GetOption

```lua
function getOption(index)
```

Gets the option at a particular index, or creates it if it doesn't exist.

This function only affects the PROShine client user interface.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the option.

## SetOptionName

```lua
function setOptionName(index, optionName)
```

Sets the name of the option at a particular index, or creates it if it doesn't exist.

This function only affects the PROShine client user interface.

### PARAMETERS

Parameter  | Type   | Description
---------- | ------ | -----------
index      | number | Index of the option.
optionName | string | Name of the option.

## SetOptionDescription

```lua
function setOptionDescription(index, optionDescription)
```

Sets the tooltip description of the option at a particular index, or creates it if it doesn't exist.

This function only affects the PROShine client user interface.

### PARAMETERS

Parameter         | Type   | Description
----------------- | ------ | -----------
index             | number | Index of the option.
optionDescription | string | Description of the option.

## RemoveOption

```lua
function removeOption(index)
```

Removes the slider option at the specified index.

This function only affects the PROShine client user interface.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
index       | number | Index of the option.

## SetTextOption

```lua
function setTextOption(index, optionText)
```

Sets the text of the TextOption at a particular index, or creates it if it doesn't exist.

This function only affects the PROShine client user interface.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
index       | number | Index of the option.
optionText  | string | Text of the specified TextOption.

## GetTextOption

```lua
function getTextOption(index)
```

Returns the text content of the TextOption at a particular index, or an empty string if it doesn't exist.

This function only affects the PROShine client user interface.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
index       | number | Index of the TextOption.

## SetTextOptionName

```lua
function setTextOptionName(index, optionName)
```

Sets the name of the TextOption at a particular index, or creates it if it doesn't exist.

This function only affects the PROShine client user interface.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
index       | number | Index of the TextOption.
optionName  | string | Name of the TextOption.

## SetTextOptionDescription

```lua
function setTextOptionDescription(index, optionDescription)
```

Sets the tooltip description of the TextOption at a particular index, or creates it if it doesn't exist.

This function only affects the PROShine client user interface.

### PARAMETERS

Parameter         | Type   | Description
----------------- | ------ | -----------
index             | number | Index of the TextOption.
optionDescription | string | Description of the TextOption.

## RemoveTextOption

```lua
function removeTextOption(index)
```

Removes the text option at the specified index.

This function only affects the PROShine client user interface.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
index       | number | Index of the TextOption.

## SetMount

```lua
function setMount(mount)
```

Sets the item that will be used to mount the player.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
mount       | string | Name of the mount.

## SetWaterMount

```lua
function setWaterMount(mount)
```

Sets the item that will be used when the player begins surfing.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
mount       | string | Name of the mount.

## LogToFile

```lua
function logToFile(file, text [, overwrite])
```

Writes a string, a number, or a table of strings and/or numbers to file. 
`overwrite` is an optional parameter, and will append the line(s) if absent.

Files must be located in `PROShine-X.X.X.X/Logs`.

### PARAMETERS

Parameter | Type    | Description
--------- | ------- | -----------
file      | string  | Name of the log file.
text      | string  | Text to log to the specified file.
overwrite | boolean | Append absent lines to file (true/false).

## ReadLinesFromFile

```lua
function readLinesFromFile(file)
```

Returns a table of every line in file.

Files must be located in `PROShine-X.X.X.X/Logs`.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
file      | string | Name of the log file.
