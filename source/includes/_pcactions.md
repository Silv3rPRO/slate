# PC actions

## ReleasePokemonFromTeam

```lua
function releasePokemonFromTeam(teamIndex)
```

Releases a pokemon from the team.

### PARAMETERS

Parameter	| 	Type	| Description
-----------	|	------	| -----------
indexTeam	|	number	| Index of the pokémon (1-6).


## ReleasePokemonFromPC

```lua
function releasePokemonFromPC(boxIndex, boxPokemonIndex)
```

Releases a pokemon from the the PC.

### PARAMETERS

Parameter		| Type   | Description
---------		| ------ | -----------
boxIndex		| number | Index of the PC Box (1-67).
boxPokemonIndex	| number | Index of the pokemon in PC Box (1-15).


## UsePC

```lua
function usePC()
```

Use the PC in the current location.

## OpenPCBox

```lua
function openPCBox(boxIndex)
```

Opens a specific Box in PC.

### PARAMETERS

Parameter	| Type   | Description
--------- 	| ------ | -----------
boxIndex	| number | Index of the PC Box (1-15).

## DepositPokemonToPC

```lua
function depositPokemonToPC(teamIndex)
```

Deposits the specified pokemon in team to PC.


### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
teamIndex     | number | Index of the pokémon (1-6).

## WithdrawPokemonFromPC

```lua
function withdrawPokemonFromPC(boxIndex, boxPokemonIndex)
```

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
boxIndex     | number | Index of the PC Box (1-67).
boxPokemonIndex     | number | Index of the pokemon in PC Box. (1-15).

## SwapPokemonFromPC

```lua
function swapPokemonFromPC(boxIndex, boxPokemonIndex, teamIndex)
```

Swaps pokemon between a specified pokemon in your team and a specified pokemon position in selected PC Box.

### PARAMETERS

Parameter | Type   | Description
--------- | ------ | -----------
boxIndex     | number | Index of the PC Box.(1-67).
boxPokemonIndex     | number | Index of the pokémon in PC Box.(1-15).
teamIndex     | number | Index of the pokémon in your team (1-6).
