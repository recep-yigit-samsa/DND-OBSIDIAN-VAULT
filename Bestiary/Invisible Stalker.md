# Invisible Stalker

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Invisible Stalker | Elemental | 6 | 97 (13d10 + 26) | 14 | walk: 50 ft., fly: {'number': 50, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Wind Swipe | 2d6 + 4 | - | - |
| Vortex | 1d8 + 3 + 2d6 | 14 | - |


**Multiattack.** The stalker makes three Wind Swipe attacks. It can replace one attack with a use of Vortex.

**Wind Swipe.** {@atkr m} {@hit 7}, reach 5 ft. {@h}11 ({@damage 2d6 + 4}) Force damage.

**Vortex.** {@actSave con} {@dc 14}, one Large or smaller creature in the stalker's space. {@actSaveFail} 7 ({@damage 1d8 + 3}) Thunder damage, and the target has the {@condition Grappled|XPHB} condition (escape {@dc 13}). Until the grapple ends, the target can't cast spells with a Verbal component and takes 7 ({@damage 2d6}) Thunder damage at the start of each of the stalker's turns.

^Tags: #monster #type_elemental