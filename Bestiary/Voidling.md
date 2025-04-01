# Voidling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Voidling | Aberration | 11 | 180 (24d10 + 48) | 15 | walk: 0 ft., fly: {'number': 50, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 17 | - |
| Shadow Tendril | 1d6 + 5 + 3d6 | - | - |
| Necrotic Bolt | 4d6 + 3 | - | - |
| Shadow's Grasp {@recharge 5} | 14d6 | 17 | - |


**Multiattack.** The voidling makes four Shadow Tendril or Necrotic Bolt attacks. If two Necrotic Bolt attacks hit one creature, the target must succeed on a {@dc 17} Wisdom saving throw or be {@condition frightened} until the end of its next turn.

**Shadow Tendril.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}8 ({@damage 1d6 + 5}) bludgeoning damage plus 10 ({@damage 3d6}) necrotic damage.

**Necrotic Bolt.** {@atk rs} {@hit 7} to hit, range 120 ft., one target. {@h}17 ({@damage 4d6 + 3}) necrotic damage.

**Shadow's Grasp {@recharge 5}.** The voidling releases a wave of small, grasping tendrils of shadow. Each creature within 20 feet of it must make a {@dc 17} Dexterity saving throw. On a failure, a creature takes 49 ({@damage 14d6}) necrotic damage and is {@condition restrained} by tendrils of shadow for 1 minute. On a success, a creature takes half the damage and isn't {@condition restrained}. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_aberration