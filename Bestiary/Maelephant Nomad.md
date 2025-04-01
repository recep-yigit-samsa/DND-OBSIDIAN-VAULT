# Maelephant Nomad

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Maelephant Nomad | Fiend | 14 | 190 (20d10 + 80) | 16 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d10 + 6 | - | - |
| Trunk | 3d6 + 6 | 18 | - |
| Noxious Breath {@recharge 5} | 12d6 | 16 | - |


**Multiattack.** The maelephant makes two attacks using its Claw, Trunk, or a combination of the two.

**Claw.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}17 ({@damage 2d10 + 6}) slashing damage.

**Trunk.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}16 ({@damage 3d6 + 6}) piercing damage. If the target is a Medium or smaller creature, it has the {@condition grappled} condition (escape {@dc 18}). Until this grapple ends, the target has the {@condition restrained} condition. While it is grappling a creature, the maelephant can't use its Trunk attack against other creatures.

**Noxious Breath {@recharge 5}.** The maelephant releases a cloud of noxious gas. All creatures in a 30-foot cone in front of the maelephant must make a {@dc 16} Constitution saving throw. Targets take 42 ({@damage 12d6}) acid damage on a failed save, or half as much damage on a successful one. In addition, on a failed save, the creature's Intelligence and Charisma scores become 1. The creature can't cast spells, activate magic items, understand language, or communicate in any intelligible way. The creature can, however, identify its friends, follow them, and even protect them. A feebled creature can repeat the save every minute, ending the effect on a success.

^Tags: #monster #type_fiend