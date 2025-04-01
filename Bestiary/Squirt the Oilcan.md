# Squirt the Oilcan

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Squirt the Oilcan | Construct | 1/4 | 17 (7d4) | 15 | walk: 0 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Slam | 1d4 + 2 | - | - |
| Boggle Oil (3 Applications) | - | 11 | - |


**Slam.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}4 ({@damage 1d4 + 2}) bludgeoning damage.

**Boggle Oil (3 Applications).** Squirt expends 1 application of boggle oil to create a 10-foot-square puddle of slippery, non-flammable oil on the ground within 5 feet of it. The puddle is {@quickref difficult terrain||3} and lasts for 1 hour. Each creature that enters the puddle's area or starts its turn there must succeed on a {@dc 11} Dexterity saving throw or fall {@condition prone}. Boggles are unaffected by the oil. After it expends all 3 applications, Squirt can't use this action again until its supply of boggle oil is replenished.

^Tags: #monster #type_construct