# Snapjaw

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Snapjaw | Beast | 5 | 170 (9d12 + 27) | 17 | walk: 30 ft., swim: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d10 + 15 | 16 | - |
| Tail | 2d8 + 15 | 16 | - |


**Multiattack.** Snapjaw makes three attacks: two with its bite and one with its tail.

**Bite.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}31 ({@damage 3d10 + 15}) piercing damage, and the target is {@condition grappled} (escape {@dc 16}). Until this grapple ends, the target is {@condition restrained}, and Snapjaw can't bite another target.

**Tail.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target not {@condition grappled} by Snapjaw. {@h}24 ({@damage 2d8 + 15}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 16} Strength saving throw or be knocked {@condition prone}.

^Tags: #monster #type_beast