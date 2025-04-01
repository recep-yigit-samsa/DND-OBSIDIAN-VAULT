# "The Demogorgon"

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| "The Demogorgon" | Giant | 8 | 123 (13d12 + 39) | 15 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Battleaxe | 2d8 + 5 | - | - |
| Morningstar | 2d8 + 5 | - | - |
| Fire Breath {@recharge 5} | 10d8 | 14 | - |
| Cold Breath {@recharge 5} | 10d8 | 14 | - |
| Gaze | - | 14 | - |
| Beguiling Gaze | - | - | - |
| Hypnotic Gaze | - | - | - |
| Insanity Gaze | - | - | - |


**Multiattack.** The ettin makes two attacks: one with its battleaxe and one with its morningstar.

**Battleaxe.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d8 + 5}) slashing damage.

**Morningstar.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d8 + 5}) piercing damage.

**Fire Breath {@recharge 5}.** The ettin's right head exhales fire in a 30-foot cone. Each creature in that area must make a {@dc 14} Dexterity saving throw, taking 45 ({@damage 10d8}) fire damage on a failed save, or half as much damage on a successful one.

**Cold Breath {@recharge 5}.** The ettin's left head exhales an icy blast in a 30-foot cone. Each creature in that area must make a {@dc 14} Constitution saving throw, taking 45 ({@damage 10d8}) cold damage on a failed save, or half as much damage on a successful one.

**Gaze.** The ettin turns its magical gaze toward one creature that it can see within 120 feet of it. That target must make a {@dc 14} Wisdom saving throw. Unless the target is {@condition incapacitated}, it can avert its eyes to avoid the gaze and to automatically succeed on the save. If the target does so, it can't see the ettin until the start of the ettin's next turn. If the target looks at the ettin in the meantime, it must immediately make the save. If the target fails the save, it suffers one of the following effects of the ettin's choice or at random:

**Beguiling Gaze.** The target is {@condition stunned} until the start of the ettin's next turn or until the ettin is no longer within line of sight.

**Hypnotic Gaze.** The target is {@condition charmed} by the ettin until the start of the ettin's next turn. The ettin chooses how the {@condition charmed} target uses its actions, reactions, and movement.

**Insanity Gaze.** The target suffers the effect of the {@spell confusion} spell without making a saving throw. The effect lasts until the start of the ettin's next turn. The ettin doesn't need to concentrate on the spell.

^Tags: #monster #type_giant