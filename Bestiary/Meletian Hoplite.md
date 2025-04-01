# Meletian Hoplite

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Meletian Hoplite | Humanoid | 3 | 49 (9d8 + 9) | 18 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Spear | 1d6 + 3 + 1d8 + 3 | - | - |
| Shield Bash | 1d4 + 3 | 13 | - |
| Ray of Frost (Cantrip) | 1d8 | - | - |


**Multiattack.** The hoplite makes three weapon attacks. It can replace one weapon attack with ray of frost.

**Spear.** {@atk mw,rw} {@hit 5} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d6 + 3}) piercing damage, or 7 ({@damage 1d8 + 3}) piercing damage if used with two hands to make a melee attack.

**Shield Bash.** {@atk mw} {@hit 5} to hit, reach 5 ft., one creature. {@h}5 ({@damage 1d4 + 3}) bludgeoning damage. If the target is a Medium or smaller creature, it must succeed on a {@dc 13} Strength saving throw or be knocked {@condition prone}.

**Ray of Frost (Cantrip).** {@atk rs} {@hit 5} to hit, range 60 ft., one creature. {@h}4 ({@damage 1d8}) cold damage, and the target's speed is reduced by 10 feet until the start of the hoplite's next turn.

^Tags: #monster #type_humanoid