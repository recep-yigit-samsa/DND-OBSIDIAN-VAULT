# Centaur Mummy

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Centaur Mummy | Undead | 6 | 85 (10d10 + 30) | 13 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pike | 1d10 + 5 | - | - |
| Hooves | 2d6 + 5 + 3d6 | 14 | - |
| Dreadful Glare | - | 12 | - |


**Multiattack.** The centaur mummy makes two melee attacks, one with its pike and one with its hooves, or it attacks with its pike and uses Dreadful Glare.

**Pike.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}10 ({@damage 1d10 + 5}) piercing damage.

**Hooves.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) piercing damage plus 10 ({@damage 3d6}) necrotic damage. If the target is a creature, it must succeed on a {@dc 14} Constitution saving throw or be cursed with mummy rot. The cursed target can't regain hit points, and its hit point maximum decreases by 10 ({@dice 3d6}) for every 24 hours that elapse. If the curse reduces the target's hit point maximum to 0, the target dies, and its body turns to dust. The curse lasts until removed by the {@spell remove curse} spell or similar magic.

**Dreadful Glare.** The centaur mummy targets one creature it can see within 60 feet of it. If the target can see the mummy, the target must succeed on a {@dc 12} Wisdom saving throw against this magic or become {@condition frightened} until the end of the mummy's next turn. If the target fails the saving throw by 5 or more, it is also {@condition paralyzed} for the same duration. A target that succeeds on the saving throw is immune to the Dreadful Glare of all mummies (but not mummy lords) for the next 24 hours.

^Tags: #monster #type_undead