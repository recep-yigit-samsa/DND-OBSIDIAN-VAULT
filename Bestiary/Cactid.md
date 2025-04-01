# Cactid

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cactid | Plant | 3 | 76 (8d10 + 32) | 14 | walk: 15 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tendril | 2d6 + 3 + 1d6 | 13 | - |
| Reel | - | - | - |


**Multiattack.** The cactid makes two Tendril attacks and uses Reel.

**Tendril.** {@atk mw} {@hit 5} to hit, reach 15 ft., one creature. {@h}10 ({@damage 2d6 + 3}) bludgeoning damage plus 3 ({@damage 1d6}) piercing damage, and the target is {@condition grappled} (escape {@dc 13}) if it is a Medium or smaller creature. Until this grapple ends, the target is {@condition restrained}, and if it isn't a Construct or Undead, the cactid begins draining fluid from the target's body. At the start of each of the {@condition grappled} creature's turns, the creature must make a {@dc 13} Constitution saving throw. On a failure, its hp maximum is reduced by 3 ({@dice 1d6}). This reduction lasts until the creature finishes a long rest after drinking at least one gallon of water. The {@condition grappled} creature dies if this effect reduces its hp maximum to 0. The cactid has two tendrils, each of which can grapple only one target.

**Reel.** The cactid pulls each creature {@condition grappled} by it up to 10 feet straight toward it.

^Tags: #monster #type_plant