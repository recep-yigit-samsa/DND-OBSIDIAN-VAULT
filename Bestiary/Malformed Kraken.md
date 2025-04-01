# Malformed Kraken

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Malformed Kraken | Monstrosity | 10 | 172 (15d12 + 75) | 17 | walk: 20 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 7 | - | - |
| Tentacle | 2d6 + 7 | 16 | - |
| Fling | 1d6 | 16 | - |
| Lightning Storm | 3d10 | 16 | - |


**Multiattack.** The kraken makes three tentacle attacks. One of them can be replaced with a bite attack, and any of them can be replaced with Fling.

**Bite.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}16 ({@damage 2d8 + 7}) piercing damage.

**Tentacle.** {@atk mw} {@hit 11} to hit, reach 20 ft., one target. {@h}14 ({@damage 2d6 + 7}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 16}). Until this grapple ends, the target is {@condition restrained}. The kraken has ten tentacles, each of which can grapple one target.

**Fling.** One Medium or smaller object held or creature {@condition grappled} by the kraken's tentacles is thrown up to 60 feet in a random direction and knocked {@condition prone}. If a thrown target strikes a solid surface, the target takes 3 ({@damage 1d6}) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a {@dc 16} Dexterity saving throw or take the same damage and be knocked {@condition prone}.

**Lightning Storm.** The kraken creates three bolts of lightning, each of which can strike a target the kraken can see within 150 feet of it. A target must make a {@dc 16} Dexterity saving throw, taking 16 ({@damage 3d10}) lightning damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_monstrosity