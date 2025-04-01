# Mi-go

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mi-go | Plant | 5 | 95 (10d8 + 50) | 17 | walk: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 3d8 + 4 | 15 | - |
| Psychic Bolt | 3d6 + 7 | - | - |
| Spore Burst {@recharge 5} | 6d6 | 15 | - |


**Multiattack.** The mi-go makes two Claw or Psychic Bolt attacks.

**Claw.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}17 ({@damage 3d8 + 4}) slashing damage, and the target is {@condition grappled} (escape {@dc 15}) if it is a Large or smaller creature.

**Psychic Bolt.** {@atk rs} {@hit 10} to hit, range 120 ft., one target. {@h}17 ({@damage 3d6 + 7}) psychic damage.

**Spore Burst {@recharge 5}.** The mi-go releases hallucinogenic spores in a 30-foot cone. Each creature in the area must make a {@dc 15} Dexterity saving throw. On a failure, a creature takes 21 ({@damage 6d6}) poison damage and is {@condition incapacitated} until the end of its next turn. On a success, a creature takes half the damage and isn't {@condition incapacitated}.

^Tags: #monster #type_plant