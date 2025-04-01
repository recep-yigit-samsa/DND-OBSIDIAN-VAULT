# Hraptnon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hraptnon | Monstrosity | 18 | 264 (16d20 + 96) | 18 | walk: 40 ft., burrow: 20 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d8 + 5 | 20 | - |
| Claws | 4d10 + 5 | - | - |
| Spine | 4d8 + 5 | 20 | - |


**Multiattack.** The hraptnon makes three melee attacks: one bite and two claws. Alternatively, the hraptnon can make two spine attacks.

**Bite.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}18 ({@damage 3d8 + 5}) piercing damage, and the target must succeed on a {@dc 20} Constitution saving throw or be {@condition incapacitated} until the end of the hraptnon's next turn.

**Claws.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}27 ({@damage 4d10 + 5}) slashing damage.

**Spine.** {@atk mw} {@hit 11} to hit, range 60 ft., one target. {@h}23 ({@damage 4d8 + 5}) piercing damage, and the target must succeed on a {@dc 20} Dexterity saving throw. On a failed save, the target is knocked {@condition prone} and {@condition restrained}. The target must escape ({@dc 20}) to remove the {@condition restrained} condition and be able to stand.

^Tags: #monster #type_monstrosity