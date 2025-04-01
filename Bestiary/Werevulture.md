# Werevulture

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Werevulture | Fiend | 4 | 75 (10d8 + 30) | 12 | walk: 30 ft., alternate: {'walk': [{'number': 10, 'condition': 'in vulture form'}, {'number': 30, 'condition': 'in hybrid form'}], 'fly': [{'number': 60, 'condition': 'in vulture or hybrid form'}]} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Beak (Vulture or Hybrid Form Only) | 2d6 + 3 | 13 | - |
| Talon | 4d4 + 3 | - | - |
| Longbow (Humanoid or Hybrid Form Only) | 2d8 + 2 | - | - |


**Multiattack.** The werevulture makes two Talon attacks, or it makes a Beak attack and a Talon attack.

**Beak (Vulture or Hybrid Form Only).** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) piercing damage. If the target is a Humanoid, it must succeed on a {@dc 13} Constitution saving throw or be cursed until targeted by the {@spell Remove Curse} spell or a similar effect. If the cursed target drops to 0 hit points, it becomes a werevulture under the DM's control and regains 10 hit points.

**Talon.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}13 ({@damage 4d4 + 3}) slashing damage.

**Longbow (Humanoid or Hybrid Form Only).** {@atk rw} {@hit 4} to hit, range 150/600 ft., one target. {@h}11 ({@damage 2d8 + 2}) piercing damage.

^Tags: #monster #type_fiend