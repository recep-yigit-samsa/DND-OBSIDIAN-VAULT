# Dragonflesh Abomination

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dragonflesh Abomination | Monstrosity | 6 | 66 (7d12 + 21) | 15 | walk: 30 ft., fly: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 1d8 + 4 + 1d10 | - | - |
| Tail | 1d12 + 4 | 15 | - |
| Acidic Spit | 3d6 | - | - |
| Acid Belch {@recharge 5} | 8d6 | 14 | - |


**Multiattack.** The abomination makes three attacks using Claw, Acidic Spit, or a combination of them. It can replace one of the attacks with a Tail attack.

**Claw.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}8 ({@damage 1d8 + 4}) slashing damage plus 5 ({@damage 1d10}) poison damage.

**Tail.** {@atk mw} {@hit 7} to hit, reach 15 ft., one target. {@h}10 ({@damage 1d12 + 4}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 15} Strength saving throw or be knocked {@condition prone}.

**Acidic Spit.** {@atk rw} {@hit 5} to hit, range 60 ft., one target. {@h}10 ({@damage 3d6}) acid damage.

**Acid Belch {@recharge 5}.** The abomination belches forth a cloud of acidic gas in a 30-foot cone. Each creature in that area must make a {@dc 14} Constitution saving throw, taking 28 ({@damage 8d6}) acid damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_monstrosity