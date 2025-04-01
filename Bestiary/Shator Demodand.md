# Shator Demodand

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Shator Demodand | Fiend | 16 | 195 (23d10 + 69) | 19 | walk: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d6 + 7 + 4d12 | 16 | - |
| Enervating Trident | 2d10 + 7 | - | - |
| Inhibitory Spray {@recharge 5} | 9d8 | 16 | - |
| Summon Demodand (1/Day) | - | - | - |


**Multiattack.** The shator makes one Bite attack and two Enervating Trident attacks.

**Bite.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}17 ({@damage 3d6 + 7}) piercing damage plus 26 ({@damage 4d12}) acid damage. If the target is a creature, it must succeed on a {@dc 16} Constitution saving throw or have the {@condition paralyzed} condition until the start of the shator's next turn.

**Enervating Trident.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}18 ({@damage 2d10 + 7}) necrotic damage.

**Inhibitory Spray {@recharge 5}.** The shator exhales a spray of slime in a line 100 feet long and 5 feet wide. Each creature in that area must make a {@dc 16} Dexterity saving throw. On a failed save, a creature takes 40 ({@damage 9d8}) acid damage and has the {@condition paralyzed} condition for 1 minute. The creature repeats the saving throw at the end of each of its turns, ending the effect on itself on a success. On a successful save, a creature takes half as much damage only.

**Summon Demodand (1/Day).** The shator has a 50 percent chance of summoning its choice of {@dice 1d4} farastu demodands, {@dice 1d2} kelubar demodands, or 1 shator demodand. A summoned demodand appears in an unoccupied space within 60 feet of the shator, acts as an ally of the shator, and can't summon other demodands. It remains for 1 minute, until it or the shator dies, or until the shator dismisses it as an action.

^Tags: #monster #type_fiend