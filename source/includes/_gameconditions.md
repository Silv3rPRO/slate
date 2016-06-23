# Game conditions

## GetPlayerX

```lua
function getPlayerX()
```

Returns the X-coordinate of the current cell.

## GetPlayerY

```lua
function getPlayerY()
```

Returns the Y-coordinate of the current cell.

## GetMapName

```lua
function getMapName()
```

Returns the name of the current map.

## GetTeamSize

```lua
function getTeamSize()
```

Returns the amount of pokémon in the team.

## GetPokemonId

```lua
function getPokemonId(index)
```

Returns the pokédex ID of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonName

```lua
function getPokemonName(index)
```

Returns the name of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonHealth

```lua
function getPokemonHealth(index)
```

Returns the current health of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonHealthPercent

```lua
function getPokemonHealthPercent(index)
```

Returns the percentage of remaining health of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonLevel

```lua
function getPokemonLevel(index)
```

Returns the level of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonStatus

```lua
function getPokemonStatus(index)
```

Returns the status of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## IsPokemonUsable

```lua
function isPokemonUsable(index)
```

Returns true if the specified pokémon is alive and has an offensive attack available.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetUsablePokemonCount

```lua
function getUsablePokemonCount()
```

Returns the amount of usable pokémon in the team.

## HasMove

```lua
function hasMove(pokemonIndex, moveName)
```

Returns true if the specified pokémon has a move with the specified name.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
pokemonIndex | number | Index of the pokémon (1-6).
moveName     | string | Name of the move (case insensitive).

## GetRemainingPowerPoints

```lua
function getRemainingPowerPoints(pokemonIndex, moveName)
```

Returns the remaining power points of the specified move of the specified pokémon in the team.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
pokemonIndex | number | Index of the pokémon (1-6).
moveName     | string | Name of the move (case insensitive).

## HasItem

```lua
function hasItem(itemName)
```

Returns true if the specified item is in the inventory.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
itemName     | string | Name of the item (case insensitive).

## GetItemQuantity

```lua
function getItemQuantity(itemName)
```

Returns the quantity of the specified item in the inventory.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
itemName     | string | Name of the item (case insensitive).

## HasPokemonInTeam

```lua
function hasPokemonInTeam(pokemonName)
```

Returns true if the specified pokémon is present in the team.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
pokemonName  | string | Name of the pokémon (case insensitive).

## IsTeamSortedByLevelAscending

```lua
function isTeamSortedByLevelAscending()
```

Returns true if the team is sorted by level in ascending order.

## IsTeamSortedByLevelDescending

```lua
function isTeamSortedByLevelDescending()
```

Returns true if the team is sorted by level in descending order.

## IsTeamRangeSortedByLevelAscending

```lua
function isTeamRangeSortedByLevelAscending(fromIndex, toIndex)
```

Returns true if the specified part of the team is sorted by level in ascending order.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
fromIndex    | number | Lower index of the range (1-5).
toIndex      | number | Upper index of the range (2-6).

## IsTeamRangeSortedByLevelDescending

```lua
function isTeamRangeSortedByLevelDescending(fromIndex, toIndex)
```

Returns true if the specified part of the team the team is sorted by level in descending order.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
fromIndex    | number | Lower index of the range (1-5).
toIndex      | number | Upper index of the range (2-6).

## IsNpcVisible

```lua
function isNpcVisible(npcName)
```

Returns true if there is a visible NPC with the specified name on the map.

If the NPC is a pokémon, its name is the character `#` followed by the pokédex ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
npcName      | string | Name of the NPC (case insensitive).

## IsNpcOnCell

```lua
function isNpcOnCell(cellX, cellY)
```

Returns true if there is a visible NPC the specified coordinates.

### PARAMETERS

Parameter  | Type   | Description
---------- | ------ | -----------
cellX      | number | X coordinate of the cell.
cellY      | number | Y coordinate of the cell.

## IsShopOpen

```lua
function isShopOpen()
```

Returns true if there is a shop opened.

## GetMoney

```lua
function getMoney()
```

Returns the amount of money in the inventory.

## IsMounted

```lua
function isMounted()
```

Returns true if the player is riding a mount or the bicycle.
