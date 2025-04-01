# Dyrrn

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dyrrn | Aberration | 24 | 325 (31d8 + 186) | 21 | walk: 40 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle Whip | 3d10 + 8 | 23 | - |
| Corruption | 4d6 + 8 | 23 | - |
| Extract Brain | 10d10 | - | - |


**Multiattack.** Dyrrn makes one Tentacle Whip attack and uses its Corruption once. Dyrrn can replace its Tentacle Whip attack with Extract Brain if it has a creature {@condition grappled}.

**Tentacle Whip.** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}24 ({@damage 3d10 + 8}) slashing damage. If the target is a Medium or smaller creature, it is {@condition grappled} (escape {@dc 23}), pulled into an unoccupied space within 5 feet of Dyrrn, and must succeed on a {@dc 23} Intelligence saving throw or be {@condition stunned} until this grapple ends. Dyrrn can't use the same tentacle whip on another target until this grapple ends. Dyrrn has two tentacle whips.

**Corruption.** Dyrrn targets one creature it can see within 60 feet of it. The target must succeed on a {@dc 23} Constitution saving throw or take 22 ({@damage 4d6 + 8}) necrotic damage and become corrupted for 1 minute. A corrupted creature's flesh twists in alien ways. The creature has disadvantage on attack rolls, its speed is reduced by half, and if it tries to cast a spell, it must first succeed on a {@dc 15} Intelligence check or the spell fails and is wasted. The corrupted creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Extract Brain.** {@atk mw} {@hit 15} to hit, reach 5 ft., one {@condition incapacitated} creature {@condition grappled} by Dyrrn. {@h}55 ({@damage 10d10}) piercing damage. If this damage reduces the target to 0 hit points, Dyrrn kills the target by extracting and devouring its brain.

^Tags: #monster #type_aberration