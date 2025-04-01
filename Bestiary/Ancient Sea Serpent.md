# Ancient Sea Serpent

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Sea Serpent | Dragon | 14 | 170 (11d20 + 55) | 17 | walk: 20 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d12 + 7 + 1d12 | - | - |
| Constrict | 4d10 + 7 | 20 | - |
| Tail | 1d12 + 7 | 20 | - |
| Rime Breath {@recharge 5} | 9d10 | 18 | - |


**Multiattack.** The sea serpent makes one Bite attack and one Constrict or Tail attack.

**Bite.** {@atk mw} {@hit 12} to hit, reach 15 ft., one target. {@h}20 ({@damage 2d12 + 7}) piercing damage plus 6 ({@damage 1d12}) cold damage.

**Constrict.** {@atk mw} {@hit 12} to hit, reach 20 ft., one creature. {@h}29 ({@damage 4d10 + 7}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 20}). Until this grapple ends, the target is {@condition restrained}, and the sea serpent can't constrict another target.

**Tail.** {@atk mw} {@hit 12} to hit, reach 20 ft., one target. {@h}13 ({@damage 1d12 + 7}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 20} Strength saving throw or be pushed up to 30 feet away from the sea serpent and knocked {@condition prone}.

**Rime Breath {@recharge 5}.** The sea serpent exhales a 60-foot cone of cold. Each creature in that area must make a {@dc 18} Constitution saving throw, taking 49 ({@damage 9d10}) cold damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_dragon