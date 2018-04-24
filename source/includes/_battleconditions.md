# Battle conditions

## IsOpponentShiny

```lua
function isOpponentShiny()
```

Returns true if the opponent pokémon is shiny.

## IsAlreadyCaught

```lua
function isAlreadyCaught()
```

Returns true if the opponent pokémon has already been caught and has a pokédex entry.

## IsWildBattle

```lua
function isWildBattle()
```

Returns true if the current battle is against a wild pokémon.

## GetActivePokemonNumber

```lua
function getActivePokemonNumber()
```

Returns the index of the active team pokémon in the current battle.

## GetOpponentId

```lua
function getOpponentId()
```

Returns the id of the opponent pokémon in the current battle.

## GetOpponentName

```lua
function getOpponentName()
```

Returns the name of the opponent pokémon in the current battle.

## GetOpponentHealth

```lua
function getOpponentHealth()
```

Returns the current health of the opponent pokémon in the current battle.

## GetOpponentHealthPercent

```lua
function getOpponentHealthPercent()
```

Returns the percentage of remaining health of the opponent pokémon in the current battle.

## GetOpponentLevel

```lua
function getOpponentLevel()
```

Returns the level of the opponent pokémon in the current battle.

## GetOpponentStatus

```lua
function getOpponentStatus()
```

Returns the status of the opponent pokémon in the current battle.

## GetOpponentForm

```lua
function getOpponentForm()
```

Returns the form of the opponent pokémon in the current battle (0 if no form).

## IsOpponentEffortValue

```lua
function isOpponentEffortValue(statType)
```

Returns true if the opponent is only giving the specified effort value.

The valid values for the stat type are:

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
statType  | string | Name of the stat (case insensitive).

## GetOpponentEffortValue

```lua
function getOpponentEffortValue(statType)
```

Returns the amount of a particular EV given by the opponent.

The valid values for the stat type are:

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
statType  | string | Name of the stat (case insensitive).

## GetOpponentType

```lua
function getOpponentType()
```

Returns the type of the opponent pokémon in the current battle as an array of length 2.
