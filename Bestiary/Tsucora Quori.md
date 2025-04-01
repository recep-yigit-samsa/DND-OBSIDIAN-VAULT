# Tsucora Quori

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tsucora Quori | Aberration | 7 | 68 (8d8 + 32) | 16 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pincer | 1d10 + 3 | 14 | - |
| Claws | 4d4 + 3 | - | - |
| Stinger | 1d10 + 3 + 3d6 | 14 | - |
| Possession {@recharge} | - | 14 | - |


**Multiattack.** The quori makes three attacks: one pincer attack, one attack with its claws, and one stinger attack.

**Pincer.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d10 + 3}) bludgeoning damage. The target is {@condition grappled} (escape {@dc 14}) if it is a Large or smaller creature. The quori has two pincers, each of which can grapple one target.

**Claws.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}13 ({@damage 4d4 + 3}) slashing damage.

**Stinger.** {@atk mw} {@hit 6} to hit, reach 10 ft., one creature. {@h}8 ({@damage 1d10 + 3}) piercing damage plus 10 ({@damage 3d6}) psychic damage, and the target must succeed on a {@dc 14} Wisdom saving throw or be {@condition frightened} of the quori for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Possession {@recharge}.** One humanoid that the quori can see within 5 feet of it must succeed on a {@dc 14} Charisma saving throw or be possessed by the quori; the quori then disappears, and the target is {@condition incapacitated} and loses control of its body. The quori now controls the body but doesn't deprive the target of awareness. The quori can't be targeted by any attack, spell, or other effect, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being {@condition charmed} and {@condition frightened}. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies. The possession lasts until the body drops to 0 hit points, the quori ends it as a bonus action, or the quori is forced out by an effect like the {@spell dispel evil and good} spell. When the possession ends, the quori reappears in an unoccupied space within 5 feet of the body. The target is immune to this quori's Possession for 24 hours after succeeding on the saving throw or after the possession ends.

^Tags: #monster #type_aberration