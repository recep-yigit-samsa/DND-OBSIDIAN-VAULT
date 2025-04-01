# Doomcaller

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Doomcaller | Fiend | 15 | 150 (20d8 + 60) | 16 | walk: 30 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Slam | 2d6 + 3 | - | - |
| Summon Fiend (1/Day) | - | - | - |


**Slam.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) bludgeoning damage, and the target has disadvantage on their next attack roll. Additionally, all attacks against the target by allies of the doomcaller are made with advantage until the start of the doomcaller's next turn.

**Summon Fiend (1/Day).** The doomcaller chooses what to summon and attempts a magical summoning. A doomcaller has a 60 percent chance of summoning {@dice 1d6} succubi or {@dice 1d4} barbed devils. A summoned fiend appears in an unoccupied space within 60 feet of its summoner, does as it pleases, and can't summon other fiends. The summoned fiend remains for 1 minute, until it or its summoner dies, or until its summoner takes a bonus action to dismiss it.

^Tags: #monster #type_fiend