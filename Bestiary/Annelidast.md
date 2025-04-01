# Annelidast

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Annelidast | Monstrosity | 12 | 184 (16d12 + 80) | 18 | walk: 40 ft., burrow: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 2d12 + 8 | 17 | - |
| Crush {@recharge 5} | 7d12 | 17 | - |


**Multiattack.** The annelidast makes three Slam attacks.

**Slam.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}21 ({@damage 2d12 + 8}) bludgeoning damage, and if the target is a creature, it must succeed on a {@dc 17} Strength saving throw or be pushed up to 15 feet away from the annelidast. A creature {@condition restrained} by the annelidast automatically succeeds on this saving throw.

**Crush {@recharge 5}.** The annelidast launches most of its massive bulk into the air and crashes down on the ground in a 20-foot line that is 10 feet wide. It then retracts itself into a space along that line and can occupy the space of one or more Large or smaller creatures. Each creature in the line must make a {@dc 17} Dexterity saving throw. On a failure, a creature takes 45 ({@damage 7d12}) bludgeoning damage, is knocked {@condition prone}, and is {@condition restrained} while it shares a space with the annelidast, as it is pinned beneath the annelidast's body. On a success, a creature takes half the damage, isn't knocked {@condition prone}, and is pushed out of the annelidast's space into an unoccupied space of the creature's choice within 5 feet of the annelidast. A creature, including the {@condition restrained} creature, can take its action to free the {@condition restrained} creature by succeeding on a {@dc 17} Strength check. If the annelidast burrows along the surface of the earth at least 20 feet before using this action, creatures in the line have disadvantage on the saving throw.

^Tags: #monster #type_monstrosity