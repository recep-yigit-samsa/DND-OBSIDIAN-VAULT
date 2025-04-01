# Solar

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Solar | Unknown | 21 | 297 (22d10 + 176) | 21 | walk: 50 ft., fly: {'number': 150, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Flying Sword | 4d6 + 8 + 8d8 | - | - |
| Slaying Bow | 4d8 + 6 + 8d8 | 21 | - |


**Multiattack.** The solar makes two Flying Sword attacks. It can replace one attack with a use of Slaying Bow.

**Flying Sword.** {@atkr m,r} {@hit 15}, reach 10 ft. or range 120 ft. {@h}22 ({@damage 4d6 + 8}) Slashing damage plus 36 ({@damage 8d8}) Radiant damage. {@hom}The sword magically returns to the solar's hand or hovers within 5 feet of the solar immediately after a ranged attack.

**Slaying Bow.** {@actSave dex} {@dc 21}, one creature the solar can see within 600 feet. {@actSaveFail} If the creature has 100 {@variantrule Hit Points|XPHB} or fewer, it dies. It otherwise takes 24 ({@damage 4d8 + 6}) Piercing damage plus 36 ({@damage 8d8}) Radiant damage.

^Tags: #monster #type_unknown