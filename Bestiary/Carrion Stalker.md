# Carrion Stalker

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Carrion Stalker | Monstrosity | 3 | 35 (10d4 + 10) | 14 | walk: 30 ft., burrow: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 1d4 + 3 | 11 | - |
| Larval Burst (1/Day) | 2d6 | 13 | - |


**Multiattack.** The carrion stalker makes three Tentacle attacks. If it is attached to a creature, it can replace one Tentacle attack with Larval Burst, if available.

**Tentacle.** {@atk mw} {@hit 5} to hit, reach 5 ft., one creature. {@h}5 ({@damage 1d4 + 3}) piercing damage, and the carrion stalker attaches to the target and pulls itself into the target's space. While attached, the carrion stalker moves with the target and has advantage on attack rolls against it. A creature can use its action to try to detach the carrion stalker and force it to move into the nearest unoccupied space, doing so with a successful {@dc 11} Strength check. On its turn, the carrion stalker can detach itself from the target by using 5 feet of movement. When it dies, the carrion stalker detaches from any creature it is attached to.

**Larval Burst (1/Day).** The carrion stalker releases a burst of larvae in a 10-foot-radius sphere centered on itself. Each creature in that area must succeed on a {@dc 13} Constitution saving throw or be {@condition poisoned}. A creature {@condition poisoned} in this way takes 7 ({@damage 2d6}) poison damage at the start of each of its turns as larvae infest its body. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Any effect that cures disease or removes the {@condition poisoned} condition instantly kills the larvae in the creature, ending the effect on it. If a creature is reduced to 0 hit points by the infestation, it dies. The larvae remain in the corpse, and one survives to become a fully grown carrion stalker in {@dice 1d4} weeks. Any effect that cures diseases or removes the {@condition poisoned} condition that targets the corpse instantly kills the larvae.

^Tags: #monster #type_monstrosity