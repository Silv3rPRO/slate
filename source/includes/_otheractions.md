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
