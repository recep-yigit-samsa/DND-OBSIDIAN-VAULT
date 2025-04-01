# Septon Modron

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Septon Modron | Construct | 12 | 204 (24d10 + 72) | 17 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., swim: 30 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 2d10 + 4 | 14 | - |
| Lightning Network | 6d10 | 16 | - |


**Multiattack.** The septon makes four Tentacle attacks and uses Lightning Network or Spellcasting.

**Tentacle.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage, and if the target is a Medium or smaller creature, it has the {@condition grappled} condition (escape {@dc 14}). Until this grapple ends, the septon can't use this tentacle against other targets. The septon has seven tentacles, each of which can grapple one target.

**Lightning Network.** The septon conjures a field of electricity that fills a 30-foot cube originating from itself before dissipating. Each creature in that area must make a {@dc 16} Dexterity saving throw. On a failed save, a creature takes 33 ({@damage 6d10}) lightning damage and has the {@condition stunned} condition for 1 minute. On a successful save, a creature takes half as much damage only. A {@condition stunned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_construct