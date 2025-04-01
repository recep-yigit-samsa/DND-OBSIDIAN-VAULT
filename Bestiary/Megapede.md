# Megapede

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Megapede | Monstrosity | 11 | 175 (13d20 + 39) | 15 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d10 + 6 + 5d8 | - | - |
| Life Drain | 3d10 | 15 | - |
| Psychic Bomb | 5d8 | 15 | - |


**Multiattack.** The megapede makes one Bite attack and uses either Life Drain or Psychic Bomb.

**Bite.** {@atk mw} {@hit 10} to hit, reach 20 ft., one target. {@h}22 ({@damage 3d10 + 6}) piercing damage plus 22 ({@damage 5d8}) poison damage.

**Life Drain.** The megapede magically drains life energy from other creatures nearby. Each creature within 15 feet of the megapede must make a {@dc 15} Constitution saving throw, taking 16 ({@damage 3d10}) necrotic damage on a failed save, or half as much damage on a successful one.

**Psychic Bomb.** The megapede targets one creature it can see within 60 feet of itself. The target must make a {@dc 15} Wisdom saving throw. On a failed save, the target takes 22 ({@damage 5d8}) psychic damage and is {@condition incapacitated} until the end of its next turn. On a successful save, the target takes half as much damage and isn't {@condition incapacitated}.

^Tags: #monster #type_monstrosity