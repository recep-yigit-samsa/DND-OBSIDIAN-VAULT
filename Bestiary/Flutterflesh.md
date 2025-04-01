# Flutterflesh

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Flutterflesh | Undead | 12 | 187 (22d10 + 66) | 16 | walk: 10 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 16 | - |
| Bone Spur | 2d12 + 4 + 2d8 | 16 | - |
| Tormenting Gaze | 4d8 + 3 | - | - |
| Creeping Death {@recharge 5} | 10d8 | 16 | - |


**Multiattack.** The flutterflesh makes three Bone Spur or Tormenting Gaze attacks. If two Tormenting Gaze attacks hit one creature, the target must succeed on a {@dc 16} Wisdom saving throw or be {@condition paralyzed} for 1 minute. A {@condition paralyzed} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Bone Spur.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}17 ({@damage 2d12 + 4}) piercing damage plus 9 ({@damage 2d8}) necrotic damage, and the flutterflesh impales the target on one of its bone spurs, grappling the target (escape {@dc 16}). The flutterflesh can have no more than two creatures impaled at a time.

**Tormenting Gaze.** {@atk rs} {@hit 7} to hit, range 120 ft., one creature. {@h}21 ({@damage 4d8 + 3}) psychic damage.

**Creeping Death {@recharge 5}.** The flutterflesh emits a wave of necromantic energy, hastening the journey toward death. Each creature within 20 feet of the flutterflesh must make a {@dc 16} Constitution saving throw, taking 45 ({@damage 10d8}) necrotic damage on a failed save, or half as much damage on a successful one. A creature below half its hp maximum has disadvantage on this saving throw.

^Tags: #monster #type_undead