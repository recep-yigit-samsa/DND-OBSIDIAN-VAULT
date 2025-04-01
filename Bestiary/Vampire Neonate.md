# Vampire Neonate

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vampire Neonate | Undead | 5 | 82 (11d8 + 33) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claws | 2d4 + 3 | 13 | - |
| Bite | 1d6 + 3 + 2d6 | - | - |
| Vampiric Glamer | - | 20 | - |
| Aura of Silence | - | - | - |


**Multiattack.** The vampire makes two attacks, only one of which can be a bite attack.

**Claws.** {@atk mw} {@hit 6} to hit, reach 5 ft., one creature. {@h}8 ({@damage 2d4 + 3}) slashing damage. Instead of dealing damage, the vampire can grapple the target (escape {@dc 13}).

**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one willing creature, or a creature that is {@condition grappled} by the vampire, {@condition incapacitated}, or {@condition restrained}. {@h}6 ({@damage 1d6 + 3}) piercing damage plus 7 ({@damage 2d6}) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

**Vampiric Glamer.** The vampire obscures its form with mind-affecting magic that makes others perceive it as a beautiful human of the same size and shape. The illusion ends if the vampire takes a bonus action to end it or if the vampire dies. A creature that can see the vampire can take an action to visually inspect it, ending the mental effect on itself and seeing the vampire's true form with a successful {@dc 20} Wisdom ({@skill Perception}) check.

**Aura of Silence.** The vampire shrouds itself in a cloak of silence to a radius of 2 feet. Within that radius, the effect is the same as the {@spell silence} spell.

^Tags: #monster #type_undead