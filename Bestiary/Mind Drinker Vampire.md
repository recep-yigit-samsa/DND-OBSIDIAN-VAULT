# Mind Drinker Vampire

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mind Drinker Vampire | Undead | 4 | 55 (10d8 + 10) | 14 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 4 + 2d6 | - | - |
| Unarmed Strike | 1d8 + 4 | 13 | - |
| Mind Siphon {@recharge 5} | 8d6 | 14 | - |


**Multiattack.** The vampire makes two attacks, only one of which can be a bite attack.

**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one willing creature, or a creature that is {@condition grappled} by the vampire, {@condition incapacitated}, or {@condition restrained}. {@h}7 ({@damage 1d6 + 4}) piercing damage plus 7 ({@damage 2d6}) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

**Unarmed Strike.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d8 + 4}) bludgeoning damage. The vampire can also grapple the target (escape {@dc 13}) if it is a creature and the vampire has a hand free.

**Mind Siphon {@recharge 5}.** The vampire targets a creature it can see within 30 feet of it. The target must make a {@dc 14} Intelligence saving throw, with disadvantage if the vampire has previously consumed the target's blood. On a failed save, the target takes 28 ({@damage 8d6}) psychic damage, and the vampire discerns the target's surface emotions and thoughts. On a successful save, the target takes half as much damage, and the vampire discerns the target's general emotional state but not its thoughts.

^Tags: #monster #type_undead