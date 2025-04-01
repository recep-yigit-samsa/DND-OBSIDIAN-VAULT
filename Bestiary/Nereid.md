# Nereid

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Nereid | Fey | 2 | 44 (8d8 + 8) | 13 | walk: 30 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Blinding Acid | 2d12 + 3 | - | - |
| Drowning Kiss {@recharge 5} | 3d12 + 3 | 13 | - |
| Water Lash | 4d6 + 3 | 13 | - |


**Blinding Acid.** {@atk ms,rs} {@hit 5} to hit, reach 5 ft. or range 30 ft., one target. {@h}16 ({@damage 2d12 + 3}) acid damage, and the target is {@condition blinded} until the start of the nereid's next turn.

**Drowning Kiss {@recharge 5}.** The nereid touches one creature it can see within 5 feet of it. The target must succeed on a {@dc 13} Constitution saving throw or take 22 ({@damage 3d12 + 3}) acid damage. On a failure, it also runs out of breath and can't speak for 1 minute. At the end of each of its turns, it can repeat the save, ending the effect on itself on a success.

**Water Lash.** The nereid causes a 5-foot cube of water within 60 feet of it to take a shape of its choice and strike one target it can see within 5 feet of that water. The target must make a {@dc 13} Strength saving throw. On a failed save, it takes 17 ({@damage 4d6 + 3}) bludgeoning damage, and if it is a Large or smaller creature, it is pushed up to 15 feet in a straight line or is knocked {@condition prone} (nereid's choice). On a successful save, the target takes half as much damage and isn't pushed or knocked {@condition prone}.

^Tags: #monster #type_fey