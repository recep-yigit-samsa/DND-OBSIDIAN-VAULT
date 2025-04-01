# Oriq Blood Mage

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Oriq Blood Mage | Unknown | 9 | 127 (15d8 + 60) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Blood Lash | 3d10 + 5 | - | - |
| Blood Boil {@recharge 4} | 7d10 | 17 | - |


**Multiattack.** The blood mage makes two Blood Lash attacks.

**Blood Lash.** {@atk ms} {@hit 9} to hit, reach 10 ft., one target. {@h}21 ({@damage 3d10 + 5}) necrotic damage. If the target is a creature, it can't regain hit points until the start of the blood mage's next turn.

**Blood Boil {@recharge 4}.** The blood mage chooses a point within 150 feet of itself, and a 20-foot radius sphere centered on that point fills with a burst of searing, blood-red mist. Each creature of the blood mage's choice that it can see in that area must make a {@dc 17} Constitution saving throw. On a failed save, a creature takes 38 ({@damage 7d10}) necrotic damage and is {@condition incapacitated} until the end of its next turn. On a success, a creature takes half as much damage and isn't {@condition incapacitated}. A creature dies if reduced to 0 hit points by this necrotic damage.

^Tags: #monster #type_unknown