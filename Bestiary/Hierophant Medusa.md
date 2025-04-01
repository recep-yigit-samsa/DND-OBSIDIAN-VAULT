# Hierophant Medusa

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hierophant Medusa | Monstrosity | 17 | 237 (25d10 + 100) | 17 | walk: 40 ft., climb: 40 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Constrict | 3d6 + 6 | 20 | - |
| Final Blade | 2d6 + 6 + 6d6 + 8d6 | 20 | - |
| Snake Hair | 1d10 + 6 + 1d10 | - | - |
| Wrathful Strike | 3d10 + 6 | - | - |


**Multiattack.** The medusa makes one Constrict attack, one Final Blade attack, and one Snake Hair attack. Alternatively, it makes two Wrathful Strike attacks.

**Constrict.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}16 ({@damage 3d6 + 6}) bludgeoning damage, and if the target is a Medium or smaller creature, it has the {@condition grappled} condition (escape {@dc 20}). Until this grapple ends, the target has the {@condition restrained} condition, and the medusa can't constrict another creature.

**Final Blade.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage plus 21 ({@damage 6d6}) force damage. If the target has at least one head and the medusa rolled a 20 on the attack roll, the target is decapitated and dies if it fails a {@dc 20} Constitution saving throw and can't survive without that head. A target is immune to this effect if it takes none of the damage, has legendary actions, or is Huge or larger. Such a creature takes an extra 28 ({@damage 8d6}) force damage from the hit.

**Snake Hair.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}11 ({@damage 1d10 + 6}) piercing damage plus 5 ({@damage 1d10}) poison damage.

**Wrathful Strike.** {@atk rs} {@hit 12} to hit, range 120 ft., one creature. {@h}22 ({@damage 3d10 + 6}) radiant damage, and the target has the {@condition blinded} condition until the end of its next turn.

^Tags: #monster #type_monstrosity