# Ancient Sapphire Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Sapphire Dragon | Unknown | {'cr': '22', 'lair': '23'} | 370 (20d20 + 160) | 20 | walk: 40 ft., burrow: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 8 + 2d10 | - | - |
| Claw | 2d6 + 8 | - | - |
| Debilitating Breath {@recharge 5} | 10d10 | 23 | - |


**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 15} to hit, reach 15 ft., one target. {@h}19 ({@damage 2d10 + 8}) piercing damage plus 11 ({@damage 2d10}) thunder damage.

**Claw.** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d6 + 8}) slashing damage.

**Debilitating Breath {@recharge 5}.** The dragon exhales a pulse of high-pitched, nearly inaudible sound in a 90-foot cone. Each creature in that area must make a {@dc 23} Constitution saving throw. On a failed save, the creature takes 55 ({@damage 10d10}) thunder damage and is {@condition incapacitated} until the end of its next turn. On a successful save, the creature takes half as much damage and isn't {@condition incapacitated}.

^Tags: #monster #type_unknown