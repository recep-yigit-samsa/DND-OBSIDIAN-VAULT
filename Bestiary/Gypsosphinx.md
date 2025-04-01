# Gypsosphinx

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gypsosphinx | Monstrosity | 14 | 190 (20d10 + 80) | 17 | walk: 40 ft., fly: 70 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | 4d6 | 18 | - |
| Beak | 1d10 + 5 | - | - |
| Claw | 4d6 + 5 | - | - |
| Carrion Breath {@recharge 5} | 6d6 + 6d8 | 18 | - |


**Multiattack.** The sphinx makes one Beak attack and two Claw attacks. If both Claw attacks hit one creature, the target must succeed on a {@dc 18} Strength saving throw or take 14 ({@damage 4d6}) slashing damage and be knocked {@condition prone}.

**Beak.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}10 ({@damage 1d10 + 5}) piercing damage.

**Claw.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}19 ({@damage 4d6 + 5}) slashing damage.

**Carrion Breath {@recharge 5}.** The gypsosphinx exhales rotting breath in a 30-foot cone. Each creature in the area must make a {@dc 18} Constitution saving throw. On a failure, a creature takes 21 ({@damage 6d6}) poison damage and 27 ({@damage 6d8}) necrotic damage and is {@condition poisoned} for 1 minute. On a success, a creature takes half the damage and isn't {@condition poisoned}. While {@condition poisoned} in this way, a creature has disadvantage on death saving throws. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_monstrosity