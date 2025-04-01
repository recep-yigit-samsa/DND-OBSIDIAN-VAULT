# Gremorly's Ghost

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gremorly's Ghost | Undead | 9 | 82 (15d8 + 15) | 12 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Withering Strike | 3d12 | - | - |
| Fell Necromancy | 7d8 + 30 | 16 | - |
| Possession {@recharge} | - | 15 | - |


**Multiattack.** Gremorly makes three Withering Strike attacks.

**Withering Strike.** {@atk ms} {@hit 8} to hit, reach 5 ft., one target. {@h}19 ({@damage 3d12}) necrotic damage.

**Fell Necromancy.** Gremorly targets one creature he can see within 60 feet of himself. The target must make a {@dc 16} Constitution saving throw, taking 61 ({@damage 7d8 + 30}) necrotic damage on a failed save, or half as much damage on a successful one. In addition, Gremorly regains 9 ({@dice 2d8}) hit points.

**Possession {@recharge}.** One Humanoid Gremorly can see within 5 feet of himself must succeed on a {@dc 15} Charisma saving throw or be possessed by him; Gremorly disappears, and the target has the {@condition incapacitated} condition and loses control of its body. Gremorly can't be targeted by any attack, spell, or other effect, except ones that turn Undead, and he retains his alignment, Intelligence, Wisdom, Charisma, and immunity to the {@condition charmed} and {@condition frightened} conditions. He otherwise uses the target's game statistics, but Gremorly doesn't gain access to the target's knowledge, class features, or proficiencies. The possession lasts until the target drops to 0 hit points, Gremorly ends it as a bonus action, or Gremorly is turned or forced out by an effect like the {@spell Dispel Evil and Good} spell. When the possession ends, Gremorly reappears in an unoccupied space within 5 feet of the target. The target is immune to this Possession for 24 hours after succeeding on the saving throw or after the possession ends.

^Tags: #monster #type_undead