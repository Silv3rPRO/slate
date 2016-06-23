# Events

## onStart

```lua
function onStart()
```

Called when the bot is started.

This is where you should initialize your variables.

## onStop

```lua
function onStop()
```

Called when the bot is stopped.

## onPause

```lua
function onPause()
```

Called when the bot is paused.

## onResume

```lua
function onPause()
```

Called when the bot is resumed from a previous pause.

## onPathAction

```lua
function onPathAction()
```

Called when the bot must execute a path action.

You should execute one (and only one) game action in this scope.

## onBattleAction

```lua
function onBattleAction()
```

Called when the bot must execute a batlle action.

You should execute one (and only one) battle action in this scope.

## onDialogMessage

```lua
function onDialogMessage(message)
```

Called when a dialog message is displayed (because you are talking to a NPC, for instance).

## onBattleMessage

```lua
function onBattleMessage(message)
```

Called when a battle message is displayed.

These messages are displayed inside the battle window in-game.

## onSystemMessage

```lua
function onSystemMessage(message)
```

Called when a system message is displayed.

These messages are displayed inside the chat in-game.

## onLearningMove

```lua
function onLearningMove(moveName, pokemonIndex)
```

Called when a pokémon is learning a move but already has four.

You can call `forgetMove` or `forgetAnyMoveExcept` here.

If you do not call these functions, the move will not be learned.

### PARAMETERS

Parameter    | Type   | Description
------------ | ------ | -----------
moveName     | string | Name of the move that can be learned
pokemonIndex | number | Index of the pokémon learning that move
