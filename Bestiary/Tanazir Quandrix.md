# Tanazir Quandrix

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tanazir Quandrix | Unknown | 24 | 444 (24d20 + 192) | 21 | walk: 40 ft., fly: {'number': 80, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d10 + 9 + 2d6 | - | - |
| Claw | 2d6 + 9 | - | - |
| Diminution Breath {@recharge 5} | 13d6 + 13d6 | 23 | - |
| Teleport | - | - | - |


**Multiattack.** Tanazir makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 16} to hit, reach 15 ft., one target. {@h}14 ({@damage 1d10 + 9}) piercing damage plus 7 ({@damage 2d6}) force damage.

**Claw.** {@atk mw} {@hit 16} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d6 + 9}) slashing damage. If the target is a creature, it is addled by recursive thoughts, reducing its speed to 0 until the start of Tanazir's next turn.

**Diminution Breath {@recharge 5}.** Tanazir exhales a weakening equation in a 90-foot cone. Each creature in that area must make a {@dc 23} Constitution saving throw. On a failed save, a creature takes 45 ({@damage 13d6}) force damage and 45 ({@damage 13d6}) psychic damage and is weakened until the start of Tanazir's next turn. While weakened, it has disadvantage on the following rolls that rely on Strength: attack rolls, ability checks, and saving throws. On a successful save, a creature takes half as much damage and isn't weakened.

**Teleport.** Tanazir teleports to an unoccupied space she can see within 100 feet of herself.

^Tags: #monster #type_unknown