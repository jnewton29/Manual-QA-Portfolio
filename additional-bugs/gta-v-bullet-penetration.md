# Grand Theft Auto V – Environment Occlusion / Bullet Penetration

## Test Environment

- **Game:** Grand Theft Auto V
- **Platforms:** PlayStation 3,4,5
- **Bug Type:** Environment Occlusion / Bullet Penetration
- **Resolution:** Unresolved

## Defect Summary

NPC projectiles were able to penetrate map geometry and damage the player character while the player was fully underground or otherwise behind solid occlusion boundaries.

## Expected Result

Solid map geometry should prevent NPC projectiles from reaching and damaging the player when the player is completely occluded from the attacking NPC.

## Actual Result

NPC projectiles penetrated the environment and continued to damage the player despite solid map geometry separating the player from the NPC.

## Evidence

No original screenshots or gameplay recordings are currently retained for this report.

## Resolution Status

Unresolved. The behavior was observed to carry forward into the PlayStation 5 version.
