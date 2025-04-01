# Greater Tyrant Shadow

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Greater Tyrant Shadow | Aberration | 22 | 372 (24d20 + 120) | 18 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 4d6 + 7 + 3d6 | - | - |
| Cloak of Shadows | - | - | - |
| Empathic Link | 4d12 + 4d12 | 22 | - |
| Shadows of Death {@recharge 5} | 8d8 | 22 | - |


**Multiattack.** The shadow makes three Claw attacks. It can replace one of the attacks with Shadows of Death (if available).

**Claw.** {@atk mw} {@hit 14} to hit, reach 5 ft., one target. {@h}21 ({@damage 4d6 + 7}) necrotic damage, plus 10 ({@damage 3d6}) psychic damage.

**Cloak of Shadows.** The shadow bends darkness around itself, and now has the {@condition invisible} condition for 1 minute. The invisibility ends if the shadow is subjected to a {@spell Daylight} spell or similar.

**Empathic Link.** The shadow attempts to form a link between itself and a creature it can see. The target must make a {@dc 22} Intelligence saving throw, taking 26 ({@damage 4d12}) psychic damage on a success. On a failed save, the creature and the shadow are linked. While linked, every time the shadow is damaged, the creature takes half of that damage as psychic damage. The creature may repeat the saving throw at the end of each of its turns, taking 26 ({@damage 4d12}) psychic damage on a failed save, or ending the effect on a successful one.

**Shadows of Death {@recharge 5}.** The shadow discharges inky-black shadows in a 90-foot-radius sphere around itself. Creatures in the shadows must succeed on a {@dc 22} Wisdom saving throw or take 36 ({@damage 8d8}) necrotic damage and have the {@condition frightened} condition for 1 minute. A {@condition frightened} creature may repeat the saving throw at the end of each of its turns, ending the effect on a successful save, but taking the damage again on a failed save.

^Tags: #monster #type_aberration