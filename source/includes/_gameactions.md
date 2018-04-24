# Game actions

## MoveToCell

```lua
function moveToCell(cellX, cellY)
```

Moves to the specified coordinates.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
cellX       | number | X coordinate of the cell
cellY       | number | Y coordinate of the cell

## MoveToMap

```lua
function moveToMap(mapName)
```

Moves to the nearest cell teleporting to the specified map.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
mapName     | string | Name of the destination map (case insensitive)

## MoveToRectangle

```lua
function moveToRectangle(minX, minY, maxX, maxY)
```

Moves to a random accessible cell inside the specified rectangle.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
minX        | number | Minimum X coordinate of the rectangle
minY        | number | Minimum Y coordinate of the rectangle 
maxX        | number | Maximum X coordinate of the rectangle 
maxY        | number | Maximum Y coordinate of the rectangle 

## MoveToNormalGround

```lua
function moveToNormalGround()
```

Move randomly avoiding water and links.

## MoveToGrass

```lua
function moveToGrass()
```

Moves to the nearest grass patch then moves randomly inside it.

## MoveToWater

```lua
function moveToWater()
```

Moves to the nearest water area then moves randomly inside it.

## MoveNearExit

```lua
function moveNearExit(mapName)
```

Moves near the cell teleporting to the specified map.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
mapName     | string | Name of the map (case insensitive)

## TalkToNpc

```lua
function talkToNpc(npcName)
```

Moves then talks to NPC specified by its name.

If the NPC is a pokémon, its name is the character `#` followed by the pokédex ID.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
npcName     | string | Name of the NPC (case insensitive)

## TalkToNpcOnCell

```lua
function talkToNpcOnCell(cellX, cellY)
```

Moves then talks to NPC located on the specified cell.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
cellX       | number | X coordinate of the cell
cellY       | number | Y coordinate of the cell

## UsePokecenter

```lua
function usePokecenter()
```

Moves to the `Nurse Joy` then talks to the cell below her.

## SwapPokemon

```lua
function swapPokemon(index1, index2)
```

Swaps the two pokémon specified by their position in the team.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
index1      | number | Index of the first pokémon to swap
index2      | number | Index of the second pokémon to swap

## SwapPokemonWithLeader

```lua
function swapPokemonWithLeader(pokemonName)
```

Swaps the first pokémon with the specified name with the leader of the team.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
pokemonName | string | Name of the pokémon to swap with the leader (case insensitive)

## SortTeamByLevelAscending

```lua
function sortTeamByLevelAscending()
```

Sorts the pokémon in the team by level in ascending order, one pokémon at a time.

## SortTeamByLevelDescending

```lua
function sortTeamByLevelDescending()
```

 Sorts the pokémon in the team by level in descending order, one pokémon at a time.

## SortTeamRangeByLevelAscending

```lua
function sortTeamRangeByLevelAscending(fromIndex, toIndex)
```

Sorts the specified part of the team by level in ascending order, one pokémon at a time.

## SortTeamRangeByLevelDescending

```lua
function sortTeamRangeByLevelDescending(fromIndex, toIndex)
```

Sorts the specified part of the team by level in descending order, one pokémon at a time.

## BuyItem

```lua
function buyItem(itemName, quantity)

buyItem("Potion", 1) -- Buys one Potion
buyItem("Poke Ball", 307) -- Buys 307 Poke Ball
```

Buys the specified item from the opened shop.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
itemName    | string | Name of the item to buy (case insensitive)
quantity    | number | Quantity of items to buy

## RelearnMove

```lua
function relearnMove(moveName)
```

Relearn a move from the move relearner NPC.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
moveName    | string | Name of the move to relearn

## UsePC

```lua
function usePC()
```

Move to the PC and opens it, refreshing the first box.

## OpenPCBox

```lua
function openPCBox(boxId)
```

Open box from the PC.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
boxId     | number | ID of the specified box.

## DepositPokemonToPC

```lua
function depositPokemonToPC(pokemonUid)
```

Deposit a pokemon to the PC.

### PARAMETERS

Parameter  | Type   | Description
---------- | ------ | -----------
pokemonUid | number | Unique ID of the specified Pokemon

## WithdrawPokemonFromPC

```lua
function withdrawPokemonFromPC(boxId, boxPokemonId)
```

Withdraw a pokemon from a known box.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon.

## SwapPokemonFromPC

```lua
function swapPokemonFromPC(boxId, boxPokemonId, pokemonUid)
```

Swap a pokemon from the team with a pokemon from the PC.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
boxId        | number | ID of the specified box.
boxPokemonId | number | PROShine unique ID of the specified pokemon to deposit.
pokemonUid   | number | Unique ID of the specified Pokemon to withdraw.

## GiveItemToPokemon

```lua
function giveItemToPokemon(itemName, pokemonIndex)
```

Give the specified item on the specified pokemon.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
itemName     | string | Name of the item (case insensitive).
pokemonIndex | number | Index of the pokémon (1-6).

## TakeItemFromPokemon

```lua
function takeItemFromPokemon(index)
```

Take the held item from the specified pokemon.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of the pokémon (1-6).

## ReleasePokemonFromTeam

```lua
function releasePokemonFromTeam(pokemonUid)
```

Releases the specified pokemon in the team.

### PARAMETERS

Parameter  | Type   | Description
---------- | ------ | -----------
pokemonUid | number | Unique ID of the specified Pokemon to withdraw.

## ReleasePokemonFromPC

```lua
function releasePokemonFromPC()
```

Releases the specified pokemon in the PC.

### PARAMETERS

Parameter  | Type   | Description
---------- | ------ | -----------
boxId      | number | ID of the specified box.
pokemonUid | number | Unique ID of the specified Pokemon to withdraw.

## EnablePrivateMessage

```lua
function enablePrivateMessage()
```

Enable private messages from users.

## DisablePrivateMessage

```lua
function disablePrivateMessage()
```

Disable private messages from users.

## EnableAutoEvolve

```lua
function enableAutoEvolve()
```

Enable auto-evolve.

## DisableAutoEvolve

```lua
function disableAutoEvolve()
```

Disable auto-evolve.
