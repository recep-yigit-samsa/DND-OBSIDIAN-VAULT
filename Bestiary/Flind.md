# Flind

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Flind | Unknown | 9 | 127 (15d8 + 60) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Flail of Madness | 1d10 + 5 | 16 | - |
| Flail of Pain | 1d10 + 5 + 4d10 | - | - |
| Flail of Paralysis | 1d10 + 5 | 16 | - |
| Longbow | 1d8 | - | - |


**Multiattack.** The flind makes three attacks: one with each of its different flail attacks or three with its longbow.

**Flail of Madness.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}10 ({@damage 1d10 + 5}) bludgeoning damage, and the target must make a {@dc 16} Wisdom saving throw. On a failed save, the target must make a melee attack against a random target within its reach on its next turn. If it has no targets within its reach even after moving, it loses its action on that turn.

**Flail of Pain.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}10 ({@damage 1d10 + 5}) bludgeoning damage plus 22 ({@damage 4d10}) psychic damage.

**Flail of Paralysis.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}10 ({@damage 1d10 + 5}) bludgeoning damage, and the target must succeed on a {@dc 16} Constitution saving throw or be {@condition paralyzed} until the end of its next turn.

**Longbow.** {@atk rw} {@hit 4} to hit, range 150/600 ft., one target. {@h}4 ({@damage 1d8}) piercing damage.

^Tags: #monster #type_unknown