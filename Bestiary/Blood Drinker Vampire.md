# Blood Drinker Vampire

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Blood Drinker Vampire | Undead | 8 | 90 (12d8 + 36) | 16 | walk: 40 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 4 + 2d6 | 15 | - |
| Rapier | 1d8 + 4 | - | - |
| Unarmed Strike | 1d8 + 3 | 14 | - |


**Multiattack.** The vampire makes three melee attacks, only one of which can be a bite attack.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one willing creature, or a creature that is {@condition grappled} by the vampire, {@condition incapacitated}, or {@condition restrained}. {@h}7 ({@damage 1d6 + 4}) piercing damage plus 7 ({@damage 2d6}) necrotic damage. If the target is humanoid, it must succeed on a {@dc 15} Charisma saving throw or be {@condition charmed} by the vampire for 1 minute. While {@condition charmed} in this way, the target is infatuated with the vampire. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

**Rapier.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d8 + 4}) piercing damage.

**Unarmed Strike.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d8 + 3}) bludgeoning damage. The vampire can also grapple the target (escape {@dc 14}) if it is a creature and the vampire has a hand free.

^Tags: #monster #type_undead