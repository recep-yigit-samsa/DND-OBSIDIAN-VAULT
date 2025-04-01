# Neh-thalggu

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Neh-thalggu | Aberration | 4 | 95 (10d10 + 40) | 14 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 2 | - | - |
| Claw | 1d4 + 2 | - | - |
| Extract Brain | 10d6 | - | - |
| Mind Blast {@recharge 5} | 2d8 | 14 | - |


**Multiattack.** The neh-thalggu makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d8 + 2}) piercing damage.

**Claw.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}4 ({@damage 1d4 + 2}) slashing damage.

**Extract Brain.** {@atk mw} {@hit 4} to hit, reach 5 ft., one {@condition incapacitated} Humanoid. {@h}35 ({@damage 10d6}) piercing damage. If this damage reduces the target to 0 hit points, the neh-thalggu kills the target by extracting and consuming its brain.

**Mind Blast {@recharge 5}.** The neh-thalggu magically emits psychic energy at one Humanoid it can see within 10 feet of itself. The target must make a {@dc 14} Wisdom saving throw. On a failed save, the target takes 9 ({@damage 2d8}) psychic damage and is {@condition incapacitated} until the end of its next turn. On a successful save, the target takes half as much damage and isn't {@condition incapacitated}.

^Tags: #monster #type_aberration