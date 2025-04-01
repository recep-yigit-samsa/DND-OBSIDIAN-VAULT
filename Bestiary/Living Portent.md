# Living Portent

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Living Portent | Celestial | 3 | 65 (10d8 + 20) | 15 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Radiant Strike | 1d12 + 3 | - | - |
| Prophetic Blessing | - | - | - |


**Multiattack.** The living portent makes two Radiant Strike attacks.

**Radiant Strike.** {@atk ms,rs} {@hit 5} to hit, reach 5 ft. or range 120 ft., one target. {@h}9 ({@damage 1d12 + 3}) radiant damage.

**Prophetic Blessing.** The living portent magically infuses the power of its prophecy into another willing creature the living portent can see within 30 feet of itself. The target's hit point maximum and current hit points increase by 7 ({@dice 1d8 + 3}), and it gains a prophecy die, a {@dice d8}. Once during each of the creature's turns, when it fails an ability check or saving throw or misses an attack roll, it can roll the prophecy die and add the number rolled to the total, potentially changing the outcome. The blessing ends after 1 hour or when the living portent ends the blessing (no action required) or uses this action again.

^Tags: #monster #type_celestial