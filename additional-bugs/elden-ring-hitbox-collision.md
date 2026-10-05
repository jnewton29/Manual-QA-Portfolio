# Elden Ring – Collision Detection / Hitbox Failure

## Test Environment

- **Game:** Elden Ring
- **Platform:** PlayStation 5
- **Version Found:** v1.0
- **Version Verified:** v1.01
- **Bug Type:** Collision Detection / Hitbox Failure

## Defect Summary

Enemies failed to register hits against the player character under specific positional conditions, allowing the player to remain untouched during active combat sequences

The behavior was captured during normal gameplay and documented with recorded gameplay footage.

## Expected Result

Enemy attacks that visually connect with the player character should register a hit and apply the appropriate damage.

## Actual Result

Under the affected conditions, enemy attacks failed to register against the player character despite the player remaining within the active combat encounter.

## Evidence

Two original gameplay recordings demonstrating the behavior were preserved through Reddit posts:

- [Gameplay Evidence 1](https://www.reddit.com/r/Eldenring/s/IOnJKl8uhR)
- [Gameplay Evidence 2](https://www.reddit.com/r/Eldenring/s/3uo6zPsVW2)

The recordings serve as the surviving visual evidence of the defect.
## Additional Observed Behavior

During testing, affected enemies could also be defeated in a single hit. This behavior was observed during the same version but is not demonstrated in the surviving gameplay evidence linked below.

## Resolution Status

Fix confirmed in Elden Ring Patch v1.01.
