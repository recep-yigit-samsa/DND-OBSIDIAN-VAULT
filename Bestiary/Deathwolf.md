# Deathwolf

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Deathwolf | Undead | 15 | 153 (18d8 + 72) | 15 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 5 + 2d8 | 16 | - |
| Claw | 2d6 + 5 + 1d8 | - | - |
| Phantom Deathwolf {@recharge 5} | 6d6 | 17 | - |


**Multiattack.** The deathwolf makes one Bite attack and two Claw attacks. It can replace one of these attacks with Phantom Deathwolf if available.

**Bite.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d8 + 5}) piercing damage plus 9 ({@damage 2d8}) necrotic damage. The target must succeed on a {@dc 16} Wisdom saving throw or have disadvantage on saving throws against the {@condition frightened} condition. This curse lasts until removed by the {@spell Remove Curse} spell or other magic.

**Claw.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) slashing damage plus 4 ({@damage 1d8}) necrotic damage.

**Phantom Deathwolf {@recharge 5}.** The deathwolf creates a terrifying phantom of itself in the mind of a creature the deathwolf can see within 60 feet of itself. The target must succeed on a {@dc 17} Intelligence saving throw or have the {@condition frightened} condition for 1 minute. While the target is {@condition frightened}, the phantom deals 21 ({@damage 6d6}) psychic damage to the target at the start of each of the target's turns. A {@condition frightened} target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_undead