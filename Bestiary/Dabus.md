# Dabus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dabus | Celestial | 2 | 44 (8d8 + 8) | 12 | walk: 20 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Flying Brick | 1d8 + 3 | - | - |
| Grasping Ground {@recharge} | 2d8 | 13 | - |


**Multiattack.** The dabus makes two Flying Brick attacks.

**Flying Brick.** {@atk rs} {@hit 5} to hit, range 90 ft., one target. {@h}7 ({@damage 1d8 + 3}) bludgeoning damage.

**Grasping Ground {@recharge}.** The dabus causes a 20-foot-square area of ground it can see within 60 feet of itself to sprout clutching appendages made of stone. Each creature of the dabus's choice in that area must succeed on a {@dc 13} Dexterity saving throw or take 9 ({@damage 2d8}) bludgeoning damage and have the {@condition grappled} condition (escape {@dc 13}). While {@condition grappled} in this way, the creature has the {@condition restrained} condition. The appendages vanish after 1 minute or if the dabus's {@status concentration} ends (as if {@status concentration||concentrating} on a spell).

^Tags: #monster #type_celestial