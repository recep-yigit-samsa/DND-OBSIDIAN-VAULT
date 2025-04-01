# Worker Robot

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Worker Robot | Construct | 3 | 75 (10d8 + 30) | 13 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Cargo Tentacle | 1d8 + 5 | 15 | - |
| Tractor Beam | - | - | - |


**Multiattack.** The robot makes two Cargo Tentacle attacks.

**Cargo Tentacle.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}9 ({@damage 1d8 + 5}) bludgeoning damage. If the target is a Medium or smaller creature, it has the {@condition grappled} condition (escape {@dc 15}). The robot has two cargo tentacles, each of which can grapple one target.

**Tractor Beam.** The robot casts {@spell Telekinesis}, targeting only creatures with the {@condition incapacitated} condition or objects. It requires no spell components and uses Wisdom as the spellcasting ability.

^Tags: #monster #type_construct