# Vættir

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vættir | Undead | 4 | 97 (13d8 + 39) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Vættir's Greataxe | 1d12 + 5 + 1d8 | - | - |
| Necrotic Bolt | 3d8 + 2 | - | - |
| Disorienting Gaze | - | 15 | - |
| Corpse Breath {@recharge 5} | 6d6 | 15 | - |


**Multiattack.** The vættir can use its Disorienting Gaze. It then makes two Vættir's Greataxe or Necrotic Bolt attacks.

**Vættir's Greataxe.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 1d12 + 5}) slashing damage plus 4 ({@damage 1d8}) necrotic damage.

**Necrotic Bolt.** {@atk rs} {@hit 4} to hit, range 120 ft., one target. {@h}15 ({@damage 3d8 + 2}) necrotic damage.

**Disorienting Gaze.** The vættir locks eyes with one creature it can see within 30 feet of it. The target must succeed on a {@dc 15} Charisma saving throw or be {@condition incapacitated} for 1 minute. While {@condition incapacitated}, the creature moves in a random direction when it moves. An {@condition incapacitated} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the vættir's Disorienting Gaze for the next 24 hours.

**Corpse Breath {@recharge 5}.** The vættir spews forth a 15‑foot cone of putrid gas. Each creature in the area must make a {@dc 15} Constitution saving throw. On a failure, a creature takes 21 ({@damage 6d6}) poison damage and is {@condition poisoned} for 1 minute. On a success, a creature takes half the damage and isn't {@condition poisoned}. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_undead