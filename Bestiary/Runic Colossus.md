# Runic Colossus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Runic Colossus | Construct | 21 | 315 (18d20 + 126) | 20 | walk: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 3d12 + 7 | - | - |
| Stomp | 4d10 + 7 | 22 | - |
| Arcane Beam {@recharge 5} | 9d12 | 22 | - |


**Multiattack.** The colossus makes two Slam attacks and then uses Stomp.

**Slam.** {@atk mw} {@hit 14} to hit, reach 20 ft., one target. {@h}26 ({@damage 3d12 + 7}) bludgeoning damage.

**Stomp.** {@atk mw} {@hit 14} to hit, reach 20 ft., one target. {@h}29 ({@damage 4d10 + 7}) bludgeoning damage. If the target is a Huge or smaller creature, it must succeed on a {@dc 22} Dexterity saving throw or have the {@condition prone} condition. Until the colossus uses its Stomp again or moves, the creature has the {@condition restrained} condition. The {@condition restrained} creature or another creature within 5 feet of it can use its action to make a {@dc 22} Strength check. On a successful check, the affected creature relocates to an unoccupied space of its choice within 5 feet of the colossus and is no longer {@condition restrained}.

**Arcane Beam {@recharge 5}.** The colossus fires a beam of magical force from its chest, hands, or head in a 150-foot line that is 10 feet wide. Each creature in that area must make a {@dc 22} Dexterity saving throw, taking 58 ({@damage 9d12}) force damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct