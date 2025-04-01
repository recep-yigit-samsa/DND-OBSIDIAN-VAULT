# Vargouille Reflection

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vargouille Reflection | Fiend | 1 | 22 (5d4 + 10) | 12 | walk: 5 ft., fly: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d6 + 2 + 3d6 | - | - |
| Abyssal Curse | - | 12 | - |
| Horrific Reflection {@recharge 5} | 3d6 | 12 | - |


**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage plus 10 ({@damage 3d6}) psychic damage.

**Abyssal Curse.** The vargouille targets one Humanoid within 5 feet of itself that has the {@condition incapacitated} condition. The target must succeed on a {@dc 12} Charisma saving throw or become cursed. The cursed target's Charisma decreases by 1 after each hour, as its head takes on fiendish aspects, and its Charisma can't increase. The curse doesn't advance while the target is in sunlight or the area of a {@spell daylight} spell. When the cursed target's Charisma becomes 2, the target dies, and its head tears from its body and becomes a new vargouille reflection. Casting remove curse, greater restoration, or a similar spell on the target before the transformation is complete ends the curse and restores the target's Charisma.

**Horrific Reflection {@recharge 5}.** The vargouille's head mimics that of a Humanoid the vargouille can see within 120 feet of itself. The target must succeed on a {@dc 12} Wisdom saving throw or take 10 ({@damage 3d6}) psychic damage and have the {@condition frightened} condition for 1 hour or until the vargouille loses {@status concentration} (as if {@status concentration||concentrating} on a spell). If the target's saving throw is successful or if the effect ends on it, the target is immune to the Horrific Reflection of all vargouille reflections for 1 hour.

^Tags: #monster #type_fiend