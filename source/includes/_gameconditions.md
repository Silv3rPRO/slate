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

## GetAccountName

```lua
function getAccountName()
```

Returns current account name.

## GetMapName

```lua
function getMapName()
```

Returns the name of the current map.

## GetPokedexOwned

```lua
function getPokedexOwned()
```

Returns Owned Entry of the pokedex.

## GetPokedexSeen

```lua
function getPokedexSeen()
```

Returns Seen Entry of the pokedex.

## GetPokedexEvolved

```lua
function getPokedexEvolved()
```

Returns Evolved Entry of the pokedex.

## GetTeamSize

```lua
function getTeamSize()
```

Returns the amount of pokémon in the team.

## IsAccountMember

```lua
function isAccountMember()
```

Returns current account's membership status.

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

## GetPokemonMaxHealth

```lua
function getPokemonMaxHealth(index)
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

## GetPokemonTotalExperience

```lua
function getPokemonTotalExperience(index)
```

Returns the experience total of a pokemon level.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonRemainingExperience

```lua
function getPokemonRemainingExperience(index)
```

Returns the remaining experience of a pokemon before next level.

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


## GetPokemonForm

```lua
function getPokemonForm(index)
```

Returns the form of the specified pokémon in the team (0 if no form).

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonHeldItem

```lua
function getPokemonHeldItem(index)
```

Returns the item held by the specified pokemon in the team, null if empty.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonUniqueId

```lua
function getPokemonUniqueId(pokemonUid)
```

PROShine unique ID of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter  | Type   | Description
---------- | ------ | -----------
pokemonUid | number | Index of the pokémon (1-6).

## IsPokemonShiny

```lua
function isPokemonShiny(index)
```

Returns the shinyness of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonMoveName

```lua
function getPokemonMoveName(index, moveId)
```

Returns the move of the specified pokémon in the team at the specified index.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).
moveId    | number | Id of the move (1-4).

## GetPokemonMoveAccuracy

```lua
function getPokemonMoveAccuracy(index, moveId)
```

Returns the move accuracy of the specified pokémon in the team at the specified index.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).
moveId    | number | Id of the move (1-4).

## GetPokemonMovePower

```lua
function getPokemonMovePower(index, moveId)
```

Returns the move power of the specified pokémon in the team at the specified index.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).
moveId    | number | Id of the move (1-4).

## GetPokemonMoveType

```lua
function getPokemonMoveType(index, moveId)
```

Returns the move type of the specified pokémon in the team at the specified index.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).
moveId    | number | Id of the move (1-4).

## GetPokemonMoveDamageType

```lua
function getPokemonMoveDamageType(index, moveId)
```

Returns the move damage type of the specified pokémon in the team at the specified index.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).
moveId    | number | Id of the move (1-4).

## GetPokemonMoveStatus

```lua
function getPokemonMoveStatus(index, moveId)
```

Returns true if the move of the specified pokémon in the team at the specified index can apply a status.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).
moveId    | number | Id of the move (1-4).

## GetPokemonNature

```lua
function getPokemonNature(index)
```

Nature of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonAbility

```lua
function getPokemonAbility(index)
```

Ability of the pokemon of the current box matching the ID.

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

## GetPokemonEffortValue

```lua
function getPokemonEffortValue(index, statType)
```

Returns the effort value for the specified stat of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).
statType  | string | Name of the stat (case insensitive).

## GetPokemonIndividualValue

```lua
function getPokemonIndividualValue(index, statType)
```

Returns the individual value for the specified stat of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).
statType  | string | Name of the stat (case insensitive).

## GetPokemonHappiness

```lua
function getPokemonHappiness(index)
```

Returns the happiness of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonRegion

```lua
function getPokemonRegion(index)
```

Returns the region of capture of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonOriginalTrainer

```lua
function getPokemonOriginalTrainer(index)
```

Returns the original trainer of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonGender

```lua
function getPokemonGender(index)
```

Returns the gender of the specified pokémon in the team.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetPokemonType

```lua
function getPokemonType(index)
```

Returns the type of the specified pokémon in the team as an array of length 2.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## GetDamageMultiplier

```lua
function getDamageMultiplier(attacker, defender)
```

Returns the multiplier of the damage type between an attacking type and one or two defending types.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
attacker  | string | Type of the attacking move.
defender  | string | Type(s) of the defending pokémon.

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

## GetActiveBattlers

```lua
function getActiveBattlers()
```

Returns an array of all NPCs that can be challenged on the current map. Format: {"npcName" = {"x" = x, "y" = y}}

## GetActiveDigSpots

```lua
function getActiveDigSpots()
```

Returns an array of all usable Dig Spots on the current map. Format: {index = {"x" = x, "y" = y}}

## GetActiveHeadbuttTrees

```lua
function getActiveHeadbuttTrees()
```

Returns an array of all usable Headbutt trees on the current map. Format: {index = {"x" = x, "y" = y}}

## GetActiveBerryTrees

```lua
function getActiveBerryTrees()
```

Returns an array of all harvestable berry trees on the current map. Format: {index = {"x" = x, "y" = y}}

## GetDiscoverableItems

```lua
function getDiscoverableItems()
```

Returns an array of all discoverable items on the currrent map. Format: {index = {"x" = x, "y" = y}}

## GetNpcData

```lua
function getNpcData()
```

Returns NPC data on current map. Format: { { "x" = x , "y" = y, "type" = type }, {...}, ... }

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

## GetPokemonMaxPowerPoints

```lua
function getPokemonMaxPowerPoints(index, moveName)
```

Max move PP of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
pokemonIndex | number | Index of the pokémon (1-6).
moveId       | number | Id of the move (1-4).

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

## HasItemId

```lua
function hasItemId(itemId)
```

Returns true if the specified item is in the inventory.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
itemId    | number | ID of the item.

## GetItemQuantityID

```lua
function getItemQuantityId(itemId)
```

Returns the quantity of the specified item in the inventory.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
itemId    | number | ID of the item.

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

## IsSurfing

```lua
function isSurfing()
```

Returns true if the player is surfing.

## IsPrivateMessageEnabled

```lua
function isPrivateMessageEnabled()
```

Check if the private message from normal users are blocked.

## GetTime

```lua
function getTime()
```

Returns the current in game hour and minute.

## IsMorning

```lua
function isMorning()
```

Returns true if morning time.

## IsNoon

```lua
function isNoon()
```

Returns true if noon time.

## IsNight

```lua
function isNight()
```

Returns true if night time.

## IsOutside

```lua
function isOutside()
```

Returns true if the character is outside.

## IsAutoEvolve

```lua
function isAutoEvolve()
```

Return the state Auto Evolve
