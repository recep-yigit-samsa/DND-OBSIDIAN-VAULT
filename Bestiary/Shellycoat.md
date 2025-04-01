# Shellycoat

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Shellycoat | Fey | 2 | 52 (7d8 + 21) | 14 | walk: 30 ft., swim: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 3 | - | - |
| Claw | 2d8 + 3 | 13 | - |
| Shellycoat's Fog (1/Day) | - | 13 | - |


**Multiattack.** The shellycoat makes one Bite attack and one Claw attack.

**Bite.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d6 + 3}) piercing damage.

**Claw.** {@atk mw} {@hit 5} to hit, reach 15 ft., one target. {@h}12 ({@damage 2d8 + 3}) slashing damage, and the target is {@condition grappled} (escape {@dc 13}) if it is a Large or smaller creature. Until this grapple ends, the creature is {@condition restrained}. The shellycoat has two claws, each of which can grapple only one creature.

**Shellycoat's Fog (1/Day).** While in contact with water, the shellycoat can create a 20-foot-radius sphere of fog centered on a point it can see within 60 feet of it for 1 minute. The sphere spreads around corners, and its area is heavily obscured. A creature that enters the fog for the first time on a turn or starts its turn there must succeed on a {@dc 13} Constitution saving throw or be {@condition poisoned} and unable to breathe, unless it can breathe water, for 1 minute. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_fey