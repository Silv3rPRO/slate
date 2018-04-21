# Battle actions

## Attack

```lua
function attack()
```

Uses the most effective offensive move available.

## WeakAttack

```lua
function weakAttack()
```

Uses the least effective offensive move available.

## Run

```lua
function run()
```

Tries to escape from the current wild battle.

## SendUsablePokemon

```lua
function sendUsablePokemon()
```

Sends the first usable pokemon different from the active one.

## SendAnyPokemon

```lua
function sendAnyPokemon()
```

Sends the first available pokemon different from the active one.

## SendPokemon

```lua
function sendPokemon(index)
```

Sends the specified pokemon to battle.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
index     | number | Index of pokémon to send

## UseMove

```lua
function useMove(moveName)
```

Uses the specified move in the current battle if available.

### PARAMETERS

Parameter   | Type   | Description
----------- | ------ | -----------
moveName    | string | Name of the move to use (case insensitive)
