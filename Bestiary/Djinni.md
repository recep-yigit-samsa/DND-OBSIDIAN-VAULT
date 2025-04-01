# Djinni

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Djinni | Unknown | 11 | 218 (19d10 + 114) | 17 | walk: 30 ft., fly: {'number': 90, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Storm Blade | 2d6 + 5 + 2d6 | - | - |
| Storm Bolt | 3d8 | - | - |
| Create Whirlwind | 6d6 | 17 | - |


**Multiattack.** The djinni makes three attacks, using Storm Blade or Storm Bolt in any combination.

**Storm Blade.** {@atkr m} {@hit 9}, reach 5 feet. {@h}12 ({@damage 2d6 + 5}) Slashing damage plus 7 ({@damage 2d6}) Lightning damage.

**Storm Bolt.** {@atkr r} {@hit 9}, range 120 feet. {@h}13 ({@damage 3d8}) Thunder damage. If the target is a Large or smaller creature, it has the {@condition Prone|XPHB} condition.

**Create Whirlwind.** The djinni conjures a whirlwind at a point it can see within 120 feet. The whirlwind fills a 20-foot-radius, 60-foot-high {@variantrule Cylinder [Area of Effect]|XPHB|Cylinder} centered on that point. The whirlwind lasts until the djinni's {@status Concentration|XPHB} on it ends. The djinni can move the whirlwind up to 20 feet at the start of each of its turns. Whenever the whirlwind enters a creature's space or a creature enters the whirlwind, that creature is subjected to the following effect. {@actSave str} {@dc 17} (a creature makes this save only once per turn, and the djinni is unaffected). {@actSaveFail} While in the whirlwind, the target has the {@condition Restrained|XPHB} condition and moves with the whirlwind. At the start of each of its turns, the {@condition Restrained|XPHB} target takes 21 ({@damage 6d6}) Thunder damage. At the end of each of its turns, the target repeats the save, ending the effect on itself on a success.

^Tags: #monster #type_unknown