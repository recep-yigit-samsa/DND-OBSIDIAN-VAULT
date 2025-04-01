# Phisarazu Spyder-Fiend

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Phisarazu Spyder-Fiend | Unknown | 13 | 170 (20d10 + 60) | 17 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 4 + 2d8 | - | - |
| Claw | 4d8 + 4 | - | - |
| Scintillating Spray {@recharge 5} | - | 16 | - |


**Multiattack.** The phisarazu makes one Bite attack and two Claw attacks. It can replace one of these attacks with Scintillating Spray if available.

**Bite.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage plus 9 ({@damage 2d8}) poison damage, and the target has the {@condition poisoned} condition until the start of the phisarazu's next turn.

**Claw.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}22 ({@damage 4d8 + 4}) slashing damage.

**Scintillating Spray {@recharge 5}.** The phisarazu expels shimmering webs in a 60-foot cone. Creatures and objects in that area are outlined by the glittering webs for 1 minute, during which time they emit dim light for 10 feet and can't benefit from the {@condition invisible} condition. Additionally, creatures in that area must succeed on a {@dc 16} Wisdom saving throw or have the {@condition stunned} condition for 1 minute. A {@condition stunned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_unknown