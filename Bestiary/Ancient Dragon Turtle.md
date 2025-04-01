# Ancient Dragon Turtle

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Dragon Turtle | Dragon | 24 | 409 (21d20 + 189) | 22 | walk: 30 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d12 + 9 + 2d12 | - | - |
| Claw | 2d8 + 9 | - | - |
| Tail | 2d10 + 9 | 24 | - |
| Steam Breath {@recharge 5} | 15d8 | 24 | - |


**Multiattack.** The dragon turtle makes one Bite or Tail attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 16} to hit, reach 15 ft., one target. {@h}15 ({@damage 1d12 + 9}) piercing damage plus 13 ({@damage 2d12}) lightning damage.

**Claw.** {@atk mw} {@hit 16} to hit, reach 15 ft., one target. {@h}18 ({@damage 2d8 + 9}) slashing damage.

**Tail.** {@atk mw} {@hit 16} to hit, reach 15 ft., one target. {@h}20 ({@damage 2d10 + 9}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 24} Strength saving throw or be knocked {@condition prone}.

**Steam Breath {@recharge 5}.** The dragon turtle exhales steam in a 90-foot cone. Each creature in that area must make a {@dc 24} Constitution saving throw, taking 67 ({@damage 15d8}) fire damage on a failed save, or half as much damage on a successful one. Being underwater doesn't grant resistance against this damage.

^Tags: #monster #type_dragon