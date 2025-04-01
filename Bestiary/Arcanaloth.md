# Arcanaloth

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Arcanaloth | Unknown | 12 | 175 (27d8 + 54) | 18 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Fiendish Burst | 4d12 + 5 | - | - |
| Banishing Claw (Requires Soul Tome) | 2d4 + 5 + 3d12 | 17 | - |


**Multiattack.** The arcanaloth makes three Fiendish Burst attacks. It can replace one attack with a Banishing Claw attack.

**Fiendish Burst.** {@atkr m,r} {@hit 9}, reach 5 ft. or range 120 ft. {@h}31 ({@damage 4d12 + 5}) Necrotic damage.

**Banishing Claw (Requires Soul Tome).** {@atkr m} {@hit 9}, reach 5 ft. {@h}10 ({@damage 2d4 + 5}) Slashing damage plus 19 ({@damage 3d12}) Psychic damage. If the target is a creature, it is subjected to the following effect. {@actSave cha} {@dc 17}. {@actSaveFail} The target is trapped in a demiplane inside the Soul Tome. While trapped there, the target has the {@condition Incapacitated|XPHB} condition. At the end of each of its turns, the target repeats the save, escaping the tome on a success. When the target escapes, it appears in the space it left or, if that space is occupied, the nearest unoccupied space. If the target fails three of these saves while in the demiplane, it becomes bound to the tome and can escape only if the tome is reduced to 0 {@variantrule Hit Points|XPHB}.

^Tags: #monster #type_unknown