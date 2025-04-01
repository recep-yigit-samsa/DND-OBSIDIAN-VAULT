# High Fae Mage

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| High Fae Mage | Unknown | 12 | 148 (27d8 + 27) | 14, 17 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Elemental Strike | 2d10 + 7 | - | - |
| Negotiate Life {@recharge 5} | 4d12 | 19 | - |


**Multiattack.** The high fae makes two Elemental Strike attacks.

**Elemental Strike.** {@atk ms,rs} {@hit 11} to hit, reach 5 ft. or range 60 ft., one target. {@h}18 ({@damage 2d10 + 7}) acid, cold, fire, force, lightning, or thunder damage (the high fae's choice).

**Negotiate Life {@recharge 5}.** The high fae enacts a magical bargain, siphoning energy from its opponents to heal its wounds. The high fae targets up to three creatures it can see within 60 feet of itself. Each target must make a {@dc 19} Constitution saving throw, taking 26 ({@damage 4d12}) necrotic damage on a failed save, or half as much damage on a successful one. The high fae then regains 30 hit points.

^Tags: #monster #type_unknown