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
function getPokemonUniqueId(index)
```

PROShine unique ID of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

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

## GetPokemonStat

```lua
function getPokemonStat(index, statType)
```

Returns the value for the specified stat of the specified pokémon in the team.

Full name | Short  | Alternative
--------- | ------ | -----------
Health    | HP     |
Attack    | ATK    |
Defence   | DEF    | Defense
SpAttack  | SPATK  |
SpDefence | SPDEF  | SpDefense
Speed     | SPD    |

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).
statType  | string | Name of the stat (case insensitive).

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

Returns the type of the specified pokémon in the team as a table of length 2.

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

Returns an array of all NPCs that can be challenged on the current map. Format: `{"npcName" = {"x" = x, "y" = y}}`.

## GetActiveDigSpots

```lua
function getActiveDigSpots()
```

Returns an array of all usable Dig Spots on the current map. Format: `{index = {"x" = x, "y" = y}}`.

## GetActiveHeadbuttTrees

```lua
function getActiveHeadbuttTrees()
```

Returns an array of all usable Headbutt trees on the current map. Format: `{index = {"x" = x, "y" = y}}`.

## GetActiveBerryTrees

```lua
function getActiveBerryTrees()
```

Returns an array of all harvestable berry trees on the current map. Format: `{index = {"x" = x, "y" = y}}`.

## GetDiscoverableItems

```lua
function getDiscoverableItems()
```

Returns an array of all discoverable items on the currrent map. Format: `{index = {"x" = x, "y" = y}}`.

## GetNpcData

```lua
function getNpcData()
```

Returns NPC data on current map. Format: `{ { "x" = x , "y" = y, "type" = type }, {...}, ... }`.

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

Returns true if auto-evolve is enabled.

## IsPCOpen

```lua
function isPCOpen()
```

Check if the PC is open. Moving close the PC, usePC() opens it.

## IsCurrentPCBoxRefreshed

```lua
function isCurrentPCBoxRefreshed()
```

Is the currentPCBox refreshed yet?

## GetCurrentPCBoxSize

```lua
function getCurrentPCBoxSize()
```

Current box size.

## GetCurrentPCBoxId

```lua
function getCurrentPCBoxId()
```

Get the active PC Box.

## GetPCBoxCount

```lua
function getPCBoxCount()
```

Return the number of non-empty boxes in the PC.

## GetPCPokemonCount

```lua
function getPCPokemonCount()
```

Return the number of pokemon in the PC.

## GetPokemonIdFromPC

```lua
function getPokemonIdFromPC(boxId, boxPokemonId)
```

Pokedex ID of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonNameFromPC

```lua
function getPokemonNameFromPC(boxId, boxPokemonId)
```

Name of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonHealthFromPC

```lua
function getPokemonHealthFromPC(boxId, boxPokemonId)
```

Current HP of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonHealthPercentFromPC

```lua
function getPokemonHealthPercentFromPC(boxId, boxPokemonId)
```

Returns the percentage of remaining health of the specified pokémon in the team.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonMaxHealthFromPC

```lua
function getPokemonMaxHealthFromPC(boxId, boxPokemonId)
```

Max HP of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonLevelFromPC

```lua
function getPokemonLevelFromPC(boxId, boxPokemonId)
```

Level of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonTotalExperienceFromPC

```lua
function getPokemonTotalExperienceFromPC(boxId, boxPokemonId)
```

Total of experience cost of a level for the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonRemainingExperienceFromPC

```lua
function getPokemonRemainingExperienceFromPC(boxId, boxPokemonId)
```

Remaining experience before the next level of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonStatusFromPC

```lua
function getPokemonStatusFromPC(boxId, boxPokemonId)
```

Status of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonTypeFromPC

```lua
function getPokemonTypeFromPC(boxId, boxPokemonId)
```

Type of the pokemon of the current box matching the ID as a table of length 2.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonHeldItemFromPC

```lua
function getPokemonHeldItemFromPC(boxId, boxPokemonId)
```

Returns the item held by the specified pokemon in the PC, null if empty.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonUniqueIdFromPC

```lua
function getPokemonUniqueIdFromPC(boxId, boxPokemonId)
```

PROShine custom unique ID of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonRemainingPowerPointsFromPC

```lua
function getPokemonRemainingPowerPointsFromPC(boxId, boxPokemonId, moveId)
```

Current move PP of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.
moveId       | number | ID of the move (1-4).

## GetPokemonMaxPowerPointsFromPC

```lua
function getPokemonMaxPowerPointsFromPC(boxId, boxPokemonId, moveId)
```

Max move PP of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.
moveId       | number | ID of the move (1-4).

## IsPokemonFromPCShiny

```lua
function IsPokemonFromPCShiny(boxId, boxPokemonId)
```

Shinyness of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonMoveNameFromPC

```lua
function getPokemonFromPC(boxId, boxPokemonId, moveId)
```

Move of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.
moveId       | number | ID of the move (1-4).

## GetPokemonMoveAccuracyFromPC

```lua
function getPokemonMoveAccuracyFromPC(boxId, boxPokemonId, moveId)
```

Returns the move accuracy of the specified pokémon in the box at the specified index.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.
moveId       | number | ID of the move (1-4).

## GetPokemonMovePowerFromPC

```lua
function getPokemonMovePowerFromPC(boxId, boxPokemonId, moveId)
```

Returns the move power of the specified pokémon in the box at the specified index.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.
moveId       | number | ID of the move (1-4).

## GetPokemonMoveTypeFromPC

```lua
function getPokemonMoveTypeFromPC(boxId, boxPokemonId, moveId)
```

Returns the move type of the specified pokémon in the box at the specified index.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.
moveId       | number | ID of the move (1-4).

## GetPokemonMoveDamageTypeFromPC

```lua
function getPokemonMoveDamageTypeFromPC(boxId, boxPokemonId, moveId)
```

Returns the move damage type of the specified pokémon in the box at the specified index.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.
moveId       | number | ID of the move (1-4).

## GetPokemonMoveStatusFromPC

```lua
function getPokemonMoveStatusFromPC(boxId, boxPokemonId, moveId)
```

Returns true if the move of the specified pokémon in the box at the specified index can apply a status.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.
moveId       | number | ID of the move (1-4).

## GetPokemonNatureFromPC

```lua
function getPokemonNatureFromPC(boxId, boxPokemonId)
```

Nature of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonAbilityFromPC

```lua
function getPokemonAbilityFromPC(boxId, boxPokemonId)
```

Ability of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonStatFromPC

```lua
function getPokemonStatFromPC(boxId, boxPokemonId, statType)
```

Returns the value for the specified stat of the specified pokémon in the PC.

Full name | Short  | Alternative
--------- | ------ | -----------
Health    | HP     |
Attack    | ATK    |
Defence   | DEF    | Defense
SpAttack  | SPATK  |
SpDefence | SPDEF  | SpDefense
Speed     | SPD    |

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.
statType     | string | Name of the stat (case insensitive).

## GetPokemonEffortValueFromPC

```lua
function getPokemonEffortValueFromPC(boxId, boxPokemonId, statType)
```

Returns the effort value for the specified stat of the specified pokémon in the PC.

Full name | Short  | Alternative
--------- | ------ | -----------
Health    | HP     |
Attack    | ATK    |
Defence   | DEF    | Defense
SpAttack  | SPATK  |
SpDefence | SPDEF  | SpDefense
Speed     | SPD    |

### PARAMETERS


Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.
statType     | string | Name of the stat (case insensitive).

## GetPokemonIndividualValueFromPC

```lua
function getPokemonIndividualValueFromPC(boxId, boxPokemonId, statType)
```

Returns the individual value for the specified stat of the specified pokémon in the PC.

Full name | Short  | Alternative
--------- | ------ | -----------
Health    | HP     |
Attack    | ATK    |
Defence   | DEF    | Defense
SpAttack  | SPATK  |
SpDefence | SPDEF  | SpDefense
Speed     | SPD    |

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.
statType     | string | Name of the stat (case insensitive).

## GetPokemonHappinessFromPC

```lua
function getPokemonHappinessFromPC(boxId, boxPokemonId)
```

Happiness of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonRegionFromPC

```lua
function getPokemonRegionFromPC(boxId, boxPokemonId)
```

Region of capture of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonOriginalTrainerFromPC

```lua
function getPokemonOriginalTrainerFromPC(boxId, boxPokemonId)
```

Original trainer of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonGenderFromPC

```lua
function getPokemonGenderFromPC(boxId, boxPokemonId)
```

Gender of the pokemon of the current box matching the ID.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetPokemonFormFromPC

```lua
function getPokemonFormFromPC(boxId, boxPokemonId)
```

Form of the pokémon in the current box matching the ID. (0 if no form.)

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## GetServer

```lua
function getServer()
```

Returns the connected server name.
