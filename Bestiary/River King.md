# River King

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| River King | Fey | 16 | 190 (20d8 + 100) | 18 | walk: 30 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Longsword | 1d8 + 5 + 1d10 + 5 + 3d6 | - | - |
| Flood Blast | 4d8 + 3 | 18 | - |
| Grasping Whirlpool {@recharge 5} | 8d8 + 4d8 | 18 | - |


**Multiattack.** The River King makes two Longsword or Flood Blast attacks.

**Longsword.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d8 + 5}) slashing damage, or 10 ({@damage 1d10 + 5}) slashing damage if used with two hands, plus 10 ({@damage 3d6}) poison damage.

**Flood Blast.** {@atk rs} {@hit 8} to hit, range 120 ft., one target. {@h}21 ({@damage 4d8 + 3}) bludgeoning damage, and the target must succeed on a {@dc 18} Strength saving throw or be pushed up to 30 feet away from the River King and knocked {@condition prone}.

**Grasping Whirlpool {@recharge 5}.** The River King magically creates a swirling vortex of water centered on a point he can see within 60 feet. The vortex appears in the shape of a cylinder that is 15 feet tall with a 10-foot radius. Each creature in the area must make a {@dc 18} Strength saving throw. On a failure, a creature takes 36 ({@damage 8d8}) bludgeoning damage and is {@condition restrained}. On a success, a creature takes half the damage, isn't {@condition restrained}, and can choose to be pushed out of the whirlpool's space. A creature that chooses not to be pushed suffers the consequences of a failed saving throw. While {@condition restrained}, a creature is unable to breathe unless it can breathe water, and it must succeed on a {@dc 18} Strength saving throw at the end of each of its turns or take 18 ({@damage 4d8}) bludgeoning damage. A creature, including the {@condition restrained} creature, can take an action to free the {@condition restrained} creature by succeeding on a {@dc 18} Strength check. A creature with a swimming speed has advantage on the saving throw and on the Strength check to escape.

^Tags: #monster #type_fey