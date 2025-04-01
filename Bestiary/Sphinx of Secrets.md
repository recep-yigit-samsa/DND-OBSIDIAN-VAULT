# Sphinx of Secrets

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sphinx of Secrets | Celestial | 8 | 136 (16d10 + 48) | 16 | walk: 40 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d8 + 4 + 2d6 | - | - |
| Curse of the Riddle | 6d6 | 15 | - |


**Multiattack.** The sphinx makes three Claw attacks. It can replace one attack with a use of {@variantrule Curses|XPHB|Curse} of the Riddle.

**Claw.** {@atkr m} {@hit 7}, reach 5 ft. {@h}13 ({@damage 2d8 + 4}) Slashing damage plus 7 ({@damage 2d6}) Radiant damage.

**Curse of the Riddle.** {@actSave int} {@dc 15}, one creature the sphinx can see within 60 feet. {@actSaveFail} 21 ({@damage 6d6}) Psychic damage, and the target is cursed with a riddle. The cursed target has {@variantrule Disadvantage|XPHB} on ability checks and attack rolls. In addition, if it takes the Magic action, it must succeed on a {@dc 15} Intelligence saving throw or that action is wasted. The cursed target can take a Study action to make a {@dc 15} Intelligence check, solving the riddle and ending the curse on a success. The curse ends early if the sphinx curses another target.

^Tags: #monster #type_celestial