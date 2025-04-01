# Gadabout

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gadabout | Plant | 1/8 | 11 (2d8 + 2) | 11 | walk: 10 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Branch | 1d4 + 1 | - | - |
| Wrap | - | 0 | - |


**Multiattack.** The gadabout makes two Branch attacks.

**Branch.** {@atk mw} {@hit 3} to hit, reach 5 ft., one target. {@h}3 ({@damage 1d4 + 1}) slashing damage.

**Wrap.** The gadabout enters the space of a willing Medium or Small creature within 5 feet of itself and gently wraps its branches around the target. The target is {@condition grappled} (escape {@dc 0}). Any attempt by the target to escape the grapple causes the gadabout to use its reaction to move into the nearest unoccupied space. While {@condition grappled} by the gadabout, the target determines where the gadabout moves on the gadabout's turns and accompanies the gadabout wherever it goes.

^Tags: #monster #type_plant