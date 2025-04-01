# Salamander

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Salamander | Elemental | 5 | 90 (12d10 + 24) | 15 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Flame Spear | 2d8 + 4 + 2d6 | - | - |
| Constrict | 2d6 + 4 + 2d6 | 15 | - |


**Multiattack.** The salamander makes two Flame Spear attacks. It can replace one attack with a use of Constrict.

**Flame Spear.** {@atkr m,r} {@hit 7}, reach 5 ft. or range 20/60 ft. {@h}13 ({@damage 2d8 + 4}) Piercing damage plus 7 ({@damage 2d6}) Fire damage. {@hom}The spear magically returns to the salamander's hand immediately after a ranged attack.

**Constrict.** {@actSave str} {@dc 15}, one Large or smaller creature the salamander can see within 10 feet. {@actSaveFail} 11 ({@damage 2d6 + 4}) Bludgeoning damage plus 7 ({@damage 2d6}) Fire damage. The target has the {@condition Grappled|XPHB} condition (escape {@dc 14}), and it has the {@condition Restrained|XPHB} condition until the grapple ends.

^Tags: #monster #type_elemental