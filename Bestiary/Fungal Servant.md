# Fungal Servant

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Fungal Servant | Undead | 15 | 97 (13d8 + 39) | 17 | walk: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rotting Fist | 3d6 + 4 + 6d6 | 16 | - |
| Dreadful Glare | - | 16 | - |


**Multiattack.** The fungal servant can use its Dreadful Glare and makes one attack with its rotting fist.

**Rotting Fist.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}14 ({@damage 3d6 + 4}) bludgeoning damage plus 21 ({@damage 6d6}) necrotic damage. If the target is a creature, it must succeed on a {@dc 16} Constitution saving throw or be cursed with mummy rot. The cursed target can't regain hit points, and its hit point maximum decreases by 10 ({@dice 3d6}) for every 24 hours that elapse. If the curse reduces the target's hit point maximum to 0, the target dies, and its body turns to spores. The curse lasts until removed by the {@spell remove curse} spell or other magic.

**Dreadful Glare.** The fungal servant targets one creature it can see within 60 feet of it. If the target can see the fungal servant, it must succeed on a {@dc 16} Wisdom saving throw against this magic or become {@condition frightened} until the end of the fungal servant's next turn. If the target fails the saving throw by 5 or more, it is also {@condition paralyzed} for the same duration. A target that succeeds on the saving throw is immune to the Dreadful Glare of all fungal servants for the next 24 hours.

^Tags: #monster #type_undead