# Nihileth Aboleth

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Nihileth Aboleth | Undead | 13 | 157 (21d10 + 42) | 17 | walk: 10 ft., swim: 40 ft., fly: {'number': 40, 'condition': '(hover) in void ghost form'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tail (Undead Form Only) | 3d6 + 5 | - | - |
| Tentacle (Undead Form Only) | 2d6 + 5 | 15 | - |
| Withering Touch (Void Ghost Form Only) | 3d6 + 4 | - | - |


**Multiattack.** The nihileth makes two Tentacle attacks and one Tail attack, or it makes three Withering Touch attacks.

**Tail (Undead Form Only).** {@atk mw} {@hit 10} to hit, reach 10 ft. one target. {@h}15 ({@damage 3d6 + 5}) bludgeoning damage.

**Tentacle (Undead Form Only).** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d6 + 5}) bludgeoning damage, and the target must succeed on a {@dc 15} Constitution saving throw or contract the nihilethic rot disease (see the Nihilethic Rot trait).

**Withering Touch (Void Ghost Form Only).** {@atk ms} {@hit 9} to hit, reach 10 ft., one creature. {@h}14 ({@damage 3d6 + 4}) necrotic damage.

^Tags: #monster #type_undead