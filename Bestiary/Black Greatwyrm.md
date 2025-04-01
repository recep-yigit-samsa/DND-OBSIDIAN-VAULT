# Black Greatwyrm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Black Greatwyrm | Unknown | 27 | 533 (26d20 + 260) | 22 | walk: 60 ft., burrow: 60 ft., fly: 120 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 10 + 2d12 | - | - |
| Claw | 2d8 + 10 | 20 | - |
| Tail | 2d8 + 10 | 26 | - |
| Breath Weapon {@recharge 5} | 12d12 | 26 | - |


**Multiattack.** The greatwyrm makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 18} to hit, reach 15 ft., one target. {@h}21 ({@damage 2d10 + 10}) piercing damage plus 13 ({@damage 2d12}) force damage.

**Claw.** {@atk mw} {@hit 18} to hit, reach 10 ft., one target. {@h}19 ({@damage 2d8 + 10}) slashing damage. If the target is a Huge or smaller creature, it is {@condition grappled} (escape {@dc 20}) and is {@condition restrained} until this grapple ends. The greatwyrm can have only one creature {@condition grappled} this way at a time.

**Tail.** {@atk mw} {@hit 18} to hit, reach 20 ft., one target. {@h}19 ({@damage 2d8 + 10}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 26} Strength saving throw or be knocked {@condition prone}.

**Breath Weapon {@recharge 5}.** The greatwyrm exhales a blast of energy in a 300-foot cone. Each creature in that area must make a {@dc 26} Dexterity saving throw. On a failed save, the creature takes 78 ({@damage 12d12}) acid damage. On a successful save, the creature takes half as much damage.

^Tags: #monster #type_unknown