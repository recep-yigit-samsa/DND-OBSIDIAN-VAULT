# Serpopard

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Serpopard | Monstrosity | 4 | 85 (10d10 + 30) | 15 | walk: 40 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 3 | - | - |
| Claw | 2d6 + 3 | - | - |
| Musk (Recharges after a Short or Long Rest) | 6d6 | 13 | - |


**Multiattack.** The serpopard makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 5} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d8 + 3}) piercing damage.

**Claw.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) slashing damage.

**Musk (Recharges after a Short or Long Rest).** The serpopard releases foul-smelling musk in a 15-foot cone. Each creature in that area must make a {@dc 13} Dexterity saving throw. On a failure, a creature takes 21 ({@damage 6d6}) poison damage and is {@condition poisoned} for 1 hour or until it spends 10 minutes washing off the musk. On a success, a creature takes half the damage and isn't {@condition poisoned}. While a creature is {@condition poisoned} in this way, any creature that starts its turn within 5 feet of the {@condition poisoned} creature must succeed on a {@dc 13} Dexterity saving throw or be {@condition poisoned} until the end of its turn.

^Tags: #monster #type_monstrosity