# Sapphire Greatwyrm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sapphire Greatwyrm | Unknown | 26 | 507 (26d20 + 234) | 21 | walk: 60 ft., burrow: 60 ft., fly: {'number': 120, 'condition': '(hover)'} ft., swim: 60 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 9 + 3d10 | - | - |
| Claw | 2d8 + 9 | 19 | - |
| Breath Weapon {@recharge 5} | 11d12 | 25 | - |
| Mass Telekinesis (Gem Awakening Only; Recharges after a Short or Long Rest) | 7d12 | 26 | - |


**Multiattack.** The greatwyrm makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 17} to hit, reach 15 ft., one target. {@h}20 ({@damage 2d10 + 9}) piercing damage plus 16 ({@damage 3d10}) force damage.

**Claw.** {@atk mw} {@hit 17} to hit, reach 10 ft., one target. {@h}18 ({@damage 2d8 + 9}) slashing damage. If the target is a Huge or smaller creature, it is {@condition grappled} (escape {@dc 19}) and is {@condition restrained} until this grapple ends. The greatwyrm can have only one creature {@condition grappled} in this way at a time.

**Breath Weapon {@recharge 5}.** The greatwyrm exhales crushing force in a 300-foot cone. Each creature in that area must make a {@dc 25} Dexterity saving throw. On a failed save, the creature takes 71 ({@damage 11d12}) force damage and is knocked {@condition prone}. On a successful save, it takes half as much damage and isn't knocked {@condition prone}. On a success or failure, the creature's speed becomes 0 until the end of its next turn.

**Mass Telekinesis (Gem Awakening Only; Recharges after a Short or Long Rest).** The greatwyrm targets any number of creatures and objects it can see within 120 feet of it. No one target can weigh more than 4,000 pounds, and objects can't be targeted if they're being worn or carried. Each targeted creature must succeed on a {@dc 26} Strength saving throw or be {@condition restrained} in the greatwyrm's telekinetic grip. At the end of a creature's turn, it can repeat the saving throw, ending the effect on itself on a success. At the end of the greatwyrm's turn, it can move each creature or object it has in its telekinetic grip up to 60 feet in any direction, but not beyond 120 feet of itself. In addition, it can choose any number of creatures {@condition restrained} in this way and deal 45 ({@damage 7d12}) force damage to each of them.

^Tags: #monster #type_unknown