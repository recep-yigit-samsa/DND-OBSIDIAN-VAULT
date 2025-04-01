# Barkburr

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Barkburr | Plant | 3 | 52 (8d6 + 24) | 16 | walk: 10 ft., climb: 10 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Poison Barb | 1d4 + 3 + 2d6 | 13 | - |
| Lignify | - | 13 | - |


**Multiattack.** The barkburr makes two Poison Barb attacks and uses Lignify if able.

**Poison Barb.** {@atk mw} {@hit 5} to hit, reach 5 ft., one creature. {@h}5 ({@damage 1d4 + 3}) piercing damage plus 7 ({@damage 2d6}) poison damage, and the barkburr attaches to the target. While the barkburr is attached, it can't make Poison Barb attacks, and the target has the {@condition restrained} condition as its body begins to transform into wood. An attached barkburr can detach itself by spending 5 feet of its movement on its turn. A creature that can reach the barkburr, including the target, can use its action to detach the barkburr by making a successful {@dc 13} Strength ({@skill Athletics}) check.

**Lignify.** The barkburr targets the creature it is attached to, and the target must make a {@dc 13} Constitution saving throw. On a failed save, the target has the {@condition petrified} condition until freed by the {@spell Greater Restoration} spell or another effect, except it turns into a tree instead of stone. Any equipment the target is wearing or carrying is absorbed into the tree's bark.

^Tags: #monster #type_plant