# Young Sea Serpent

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Sea Serpent | Dragon | 8 | 123 (13d12 + 39) | 16 | walk: 10 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 4 + 1d10 | - | - |
| Constrict | 4d8 + 4 | 15 | - |
| Tail | 1d10 + 4 | 15 | - |
| Rime Breath {@recharge 5} | 7d10 | 14 | - |


**Multiattack.** The sea serpent makes one Bite attack and one Constrict or Tail attack.

**Bite.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage plus 5 ({@damage 1d10}) cold damage.

**Constrict.** {@atk mw} {@hit 7} to hit, reach 20 ft., one creature. {@h}22 ({@damage 4d8 + 4}) bludgeoning damage. If the target is Large or smaller, it is {@condition grappled} (escape {@dc 15}). Until this grapple ends, the target is {@condition restrained}, and the sea serpent can't constrict another target.

**Tail.** {@atk mw} {@hit 7} to hit, reach 15 ft., one target. {@h}9 ({@damage 1d10 + 4}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 15} Strength saving throw or be pushed up to 20 feet away and knocked {@condition prone}.

**Rime Breath {@recharge 5}.** The sea serpent exhales a 30-foot cone of cold. Each creature in that area must make a {@dc 14} Constitution saving throw, taking 38 ({@damage 7d10}) cold damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_dragon