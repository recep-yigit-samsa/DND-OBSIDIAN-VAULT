# Krake Spawn

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Krake Spawn | Monstrosity | 14 | 175 (14d12 + 84) | 16 | walk: 20 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d10 + 7 | - | - |
| Tentacle | 1d6 + 7 | 17 | - |
| Freezing Water Bolt | 2d8 + 4 + 3d6 | - | - |
| Ink Cloud {@recharge 5} | 10d10 | 17 | - |
| Vomit Forth the Deeps {@recharge 5} | 6d8 + 5d10 | 17 | - |


**Multiattack.** The krake spawn makes one Bite attack and eight Tentacle attacks, or it makes four Freezing Water Bolt attacks.

**Bite.** {@atk mw} {@hit 12} to hit, reach 10 ft, one target. {@h}12 ({@damage 1d10 + 7}) slashing damage.

**Tentacle.** {@atk mw} {@hit 12} to hit, reach 15 ft., one target. {@h}10 ({@damage 1d6 + 7}) bludgeoning damage. If the target is a Large or smaller creature, it is {@condition grappled} (escape {@dc 17}). Until this grapple ends, the target is {@condition restrained}. The krake spawn has eight tentacles, each of which can grapple only one target.

**Freezing Water Bolt.** {@atk rs} {@hit 9} to hit, range 60 ft., one target. {@h}13 ({@damage 2d8 + 4}) bludgeoning damage plus 10 ({@damage 3d6}) cold damage.

**Ink Cloud {@recharge 5}.** While underwater, the krake spawn emits a 20-foot-radius cloud of ink all around itself. Each creature in the cloud must make a {@dc 17} Constitution saving throw, taking 55 ({@damage 10d10}) poison damage on a failed save, or half as much damage on a successful one. The area is heavily obscured for 1 minute, although a significant current can disperse the ink.

**Vomit Forth the Deeps {@recharge 5}.** The krake spawn sprays half‑digested food from its maw in a 30-foot cone. Each creature in the area must make a {@dc 17} Dexterity saving throw. On a failure, a creature takes 27 ({@damage 6d8}) acid damage plus 27 ({@damage 5d10}) poison damage and is {@condition incapacitated}. On a success, a creature takes half the damage and isn't {@condition incapacitated}.

^Tags: #monster #type_monstrosity