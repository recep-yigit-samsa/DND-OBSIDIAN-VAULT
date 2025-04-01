# Vampire Nightbringer

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vampire Nightbringer | Undead | 8 | 142 (19d8 + 57) | 16 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 4 + 3d6 | - | - |
| Shadow Strike | 1d6 + 4 + 4d6 | - | - |


**Multiattack.** The vampire makes one Bite attack and one Shadow Strike attack.

**Bite.** {@atkr m} {@hit 7}, reach 5 ft. {@h}7 ({@damage 1d6 + 4}) Piercing damage plus 10 ({@damage 3d6}) Necrotic damage. The target's {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by an amount equal to the Necrotic damage taken, and the vampire regains {@variantrule Hit Points|XPHB} equal to that amount.

**Shadow Strike.** {@atkr m} {@hit 7}, reach 5 ft. {@h}7 ({@damage 1d6 + 4}) Slashing damage plus 14 ({@damage 4d6}) Cold damage.

^Tags: #monster #type_undead