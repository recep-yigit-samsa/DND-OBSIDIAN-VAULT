# Vampiric Mind Flayer

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vampiric Mind Flayer | Undead | 5 | 85 (10d8 + 40) | 15 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 1d8 + 4 + 3d6 | - | - |
| Tentacles | 1d6 + 4 | 15 | - |
| Drink Sapience | 4d6 | 15 | - |


**Multiattack.** The mind flayer makes two Claw attacks or one Claw attack and one Tentacles attack.

**Claw.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d8 + 4}) slashing damage plus 10 ({@damage 3d6}) necrotic damage.

**Tentacles.** {@atk mw} {@hit 7} to hit, reach 5 ft., one creature. {@h}7 ({@damage 1d6 + 4}) piercing damage, and if the target is a creature, it is {@condition grappled} (escape {@dc 15}).

**Drink Sapience.** The mind flayer targets one creature it is grappling. The target must succeed on a {@dc 15} Wisdom saving throw or take 14 ({@damage 4d6}) psychic damage and gain 1 level of {@condition exhaustion}. The mind flayer regains a number of hit points equal to the psychic damage dealt. A creature reduced to 0 hit points by the psychic damage dies.

^Tags: #monster #type_undead