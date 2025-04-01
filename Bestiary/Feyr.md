# Feyr

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Feyr | Aberration | 5 | 88 (16d10) | 16 | walk: 0 ft., fly: {'number': 50, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Frightful Bite | 1d10 + 3 | 13 | - |
| Tentacle | 4d6 + 3 | 13 | - |
| Invisibility | - | - | - |
| Nightmare Fuel (1/Day) | 5d10 | 13 | - |


**Multiattack.** The feyr makes one Frightful Bite attack and one Tentacle attack.

**Frightful Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one creature. {@h}8 ({@damage 1d10 + 3}) piercing damage, and each creature within 10 feet of the feyr that can see it must succeed on a {@dc 13} Wisdom saving throw or be {@condition frightened} of the feyr until the end of the feyr's next turn.

**Tentacle.** {@atk mw} {@hit 6} to hit, reach 10 ft., one creature. {@h}17 ({@damage 4d6 + 3}) psychic damage, and the target is {@condition grappled} (escape {@dc 13}). Until this grapple ends, the feyr can't use this tentacle against other targets. The feyr has two tentacles, each of which can grapple one creature.

**Invisibility.** The feyr becomes {@condition invisible} until it attacks, uses Nightmare Fuel, or uses a bonus action to become visible.

**Nightmare Fuel (1/Day).** The feyr targets one {@condition unconscious} creature it can see within 10 feet of itself. The target must succeed on a {@dc 13} Wisdom saving throw or take 27 ({@damage 5d10}) psychic damage, and the feyr gains temporary hit points equal to the damage dealt.

^Tags: #monster #type_aberration