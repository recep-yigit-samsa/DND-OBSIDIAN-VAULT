# Morkoth

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Morkoth | Aberration | {'cr': '11', 'lair': '12'} | 130 (20d8 + 40) | 17 | walk: 25 ft., swim: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 2 | - | - |
| Tentacles | 3d8 + 2 + 3d8 + 2 | 14 | - |
| Hypnosis | - | 17 | - |


**Multiattack.** The morkoth makes three attacks: two with its bite and one with its tentacles or three with its bite.

**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}9 ({@damage 2d6 + 2}) slashing damage.

**Tentacles.** {@atk mw} {@hit 6} to hit, reach 15 ft., one target. {@h}15 ({@damage 3d8 + 2}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 14}) if it is a Large or smaller creature. Until this grapple ends. the target is {@condition restrained} and takes 15 ({@damage 3d8 + 2}) bludgeoning damage at the start of each of the morkoth's turns. and the morkoth can't use its tentacles on another target.

**Hypnosis.** The morkoth projects a 30-foot cone of magical energy. Each creature in that area must make a {@dc 17} Wisdom saving throw. On a failed save, the creature is {@condition charmed} by the morkoth for 1 minute. While {@condition charmed} in this way, the target tries to get as close to the morkoth as possible, using its actions to Dash until it is within 5 feet of the morkoth. A {@condition charmed} target can repeat the saving throw at the end of each of its turns and whenever it takes damage, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature has advantage on saving throws against the morkoth's Hypnosis for 24 hours.

^Tags: #monster #type_aberration