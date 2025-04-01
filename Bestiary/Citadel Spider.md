# Citadel Spider

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Citadel Spider | Monstrosity | 18 | 310 (20d20 + 150) | 18 | walk: 50 ft., climb: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 8 + 2d6 | - | - |
| Web Bomb | 3d10 + 8 + 3d6 | 19 | - |


**Multiattack.** The spider makes two Bite attacks. It can replace one of these attacks with a use of Web Bomb.

**Bite.** {@atk mw} {@hit 14} to hit, reach 20 ft., one target. {@h}19 ({@damage 2d10 + 8}) piercing damage plus 7 ({@damage 2d6}) poison damage.

**Web Bomb.** {@atk rw} {@hit 14} to hit, range 300 ft./600 ft., one target. {@h}24 ({@damage 3d10 + 8}) bludgeoning damage, and the target and all creatures within 10 feet of it must succeed on a {@dc 19} Dexterity saving throw or take 10 ({@damage 3d6}) acid damage and have the {@condition restrained} condition until the start of the spider's next turn.

^Tags: #monster #type_monstrosity