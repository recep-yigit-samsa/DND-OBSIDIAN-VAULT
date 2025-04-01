# Planewatcher

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Planewatcher | Celestial | 10 | 136 (16d8 + 64) | 18 | walk: 30 ft., climb: 90 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Radiant Lasso | 4d6 + 4 | 16 | - |
| Enervating Blast | 4d8 + 5 | - | - |
| Planar Ultimatum | 10d8 | 17 | - |


**Multiattack.** The planewatcher makes one Radiant Lasso attack and two Enervating Blast attacks, or it makes three Enervating Blast attacks. It can replace two attacks with a use of Planar Ultimatum.

**Radiant Lasso.** {@atk mw} {@hit 8} to hit, reach 30 ft., one target. {@h}22 ({@damage 4d6 + 4}) radiant damage, and the target is {@condition grappled} (escape {@dc 16}) if the planewatcher isn't already grappling a creature. Until this grapple ends, the target is {@condition restrained}, can't tell a lie, and can't teleport or be transported to another plane of existence unless the planewatcher wills it.

**Enervating Blast.** {@atk ms,rs} {@hit 9} to hit, range 60 ft., one target. {@h}23 ({@damage 4d8 + 5}) force damage, and the target has disadvantage on Strength and Dexterity checks until the end of its next turn.

**Planar Ultimatum.** The planewatcher demands one creature {@condition grappled} by it to return to the creature's home plane within 24 hours. If the creature doesn't swear to do so, it must make a {@dc 17} Constitution saving throw, taking 45 ({@damage 10d8}) radiant damage on a failed save, or half as much damage on a successful one If the creature swears to return, it becomes affected by the {@spell geas} spell for 30 days, which compels the creature to return to its home plane as soon as possible.

^Tags: #monster #type_celestial