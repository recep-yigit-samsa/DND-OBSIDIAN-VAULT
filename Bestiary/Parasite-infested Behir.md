# Parasite-infested Behir

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Parasite-infested Behir | Undead | 11 | 168 (16d12 + 64) | 17 | walk: 50 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d10 + 6 | - | - |
| Constrict | 2d10 + 6 + 2d10 + 6 | 16 | - |
| Lightning Breath {@recharge 5} | 12d10 | 16 | - |
| Swallow | 6d6 + 8d8 | 19 | - |


**Multiattack.** The behir makes two attacks: one with its bite and one to constrict.

**Bite.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}22 ({@damage 3d10 + 6}) piercing damage.

**Constrict.** {@atk mw} {@hit 10} to hit, reach 5 ft., one Large or smaller creature. {@h}17 ({@damage 2d10 + 6}) bludgeoning damage plus 17 ({@damage 2d10 + 6}) slashing damage. The target is {@condition grappled} (escape {@dc 16}) if the behir isn't already constricting a creature, and the target is {@condition restrained} until this grapple ends.

**Lightning Breath {@recharge 5}.** The behir exhales a line of lightning that is 20 feet long and 5 feet wide. Each creature in that line must make a {@dc 16} Dexterity saving throw, taking 66 ({@damage 12d10}) lightning damage on a failed save, or half as much damage on a successful one.

**Swallow.** The behir makes one bite attack against a Medium or smaller target it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the behir, and it takes 21 ({@damage 6d6}) acid damage at the start of each of the behir's turns. A behir can have only one creature swallowed at a time. Any creature swallowed by a parasite-infested behir must succeed on a {@dc 19} Constitution saving throw at the start of each of the behir's turns or be feasted upon by blood parasites, taking 36 ({@damage 8d8}) necrotic damage on a failed save, or half as much damage on a successful save. This damage is in addition to the damage caused by the behir's digestive acids. If the behir takes 30 damage or more on a single turn from the swallowed creature, the behir must succeed on a {@dc 14} Constitution saving throw at the end of that turn or regurgitate the creature, which falls {@condition prone} in a space within 10 feet of the behir. If the behir dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 15 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_undead