# Oni

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Oni | Fiend | 7 | 119 (14d10 + 42) | 17 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 1d12 + 4 + 2d8 | - | - |
| Nightmare Ray | 2d6 + 2 | - | - |
| Shape-Shift | - | - | - |


**Multiattack.** The oni makes two Claw or Nightmare Ray attacks. It can replace one attack with a use of Spellcasting.

**Claw.** {@atkr m} {@hit 7}, reach 10 ft. {@h}10 ({@damage 1d12 + 4}) Slashing damage plus 9 ({@damage 2d8}) Necrotic damage.

**Nightmare Ray.** {@atkr r} {@hit 5}, range 60 ft. {@h}9 ({@damage 2d6 + 2}) Psychic damage, and the target has the {@condition Frightened|XPHB} condition until the start of the oni's next turn.

**Shape-Shift.** The oni shape-shifts into a Small or Medium Humanoid or a Large Giant, or it returns to its true form. Other than its size, its game statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed.

^Tags: #monster #type_fiend