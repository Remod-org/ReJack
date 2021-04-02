# ReJack
Field-refill your jackhammer and do other useful things

The useless plugin no-one asked for, aka an excuse for not working on other stuff I should be working on.

1. Allows for field reloading of a jackhammer by pressing the reload key when held.
2. Allows for repair of a broken jackhammer via the /rejack command.
3. Allows for the jackhammer to be used for faster repair

## Commands
  - /rejack -- Repair a broken jackhammer - command required since a broken item cannot be held
  - /repjack -- Turns the jackhammer into a repair tool for up to the number of seconds configured (repjacktime).  Chat messages sent on activation/deactivation


## Configuration
```json
{
  "Options": {
    "usePermission": false,
    "repairFully": false,
    "repjacktime": 30.0
  },
  "Version": {
    "Major": 1,
    "Minor": 0,
    "Patch": 1
  }
}
```
  - usePermission -- Require permissions for reload, and /rejack and /repjack commands
  - repairFully -- Attempt to fix the jackhammer fully, removing wear condition
  - repjackTime -- How long /repjack is active

## Permissions
  - rejack.use -- If usePermission is set, require this permission to use the plugin

