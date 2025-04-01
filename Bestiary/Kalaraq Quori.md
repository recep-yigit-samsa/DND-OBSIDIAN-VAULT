# Kalaraq Quori

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Kalaraq Quori | Aberration | 19 | 161 (19d8 + 76) | 18 | walk: 30 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Arcane Blast | 1d10 + 7 | - | - |
| Soul Binding | 4d10 + 7 | - | - |
| Mind Seed (1/Day) | - | 21 | - |
| Swarm of Eyes {@recharge} | 10d8 | 21 | - |
| Possession {@recharge} | - | 21 | - |


**Multiattack.** The quori makes two Soul Binding attacks. Alternatively, it can make four attacks with Arcane Blast.

**Arcane Blast.** {@atk rs} {@hit 13} to hit, range 120 ft., one target. {@h}12 ({@damage 1d10 + 7}) force damage.

**Soul Binding.** {@atk ms} {@hit 13} to hit, reach 5 ft., one target. {@h}29 ({@damage 4d10 + 7}) necrotic damage. A creature reduced to 0 hit points from this attack dies and has its soul imprisoned in one of the quori's eyes. The target can't be revived by any means short of a {@spell wish} spell until the quori is destroyed.

**Mind Seed (1/Day).** The quori touches one humanoid, which must succeed on a {@dc 21} Intelligence saving throw or be cursed. The curse lasts until it's removed by a remove curse or {@spell greater restoration} spell. The cursed target suffers 1 level of {@condition exhaustion} every 24 hours, and finishing a long rest doesn't reduce its {@condition exhaustion}. If the cursed target reaches {@condition exhaustion} level 6, it doesn't die; it instead becomes a thrall under the quori's control, and all its {@condition exhaustion} is removed. Only the {@spell wish} spell can free the thrall from this control.

**Swarm of Eyes {@recharge}.** The quori creates a swarm of spectral eyes that fills a 30-foot-radius sphere centered on a point it can see within 60 feet of it. Each creature in that area must make a {@dc 21} Wisdom saving throw. On a failure, a creature takes 45 ({@damage 10d8}) psychic damage, and it is {@condition blinded} for 1 minute. On a success, a creature takes half as much damage and isn't {@condition blinded}. A {@condition blinded} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Possession {@recharge}.** One humanoid that the quori can see within 5 feet of it must succeed on a {@dc 21} Charisma saving throw or be possessed by the quori; the quori then disappears, and the target is {@condition incapacitated} and loses control of its body. The quori now controls the body but doesn't deprive the target of awareness. The quori can't be targeted by any attack, spell, or other effect, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being {@condition charmed} and {@condition frightened}. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies. The possession lasts until the body drops to 0 hit points, the quori ends it as a bonus action, or the quori is forced out by an effect like the {@spell dispel evil and good} spell. When the possession ends, the quori reappears in an unoccupied space within 5 feet of the body. The target is immune to this quori's Possession for 24 hours after succeeding on the saving throw or after the possession ends.

^Tags: #monster #type_aberration