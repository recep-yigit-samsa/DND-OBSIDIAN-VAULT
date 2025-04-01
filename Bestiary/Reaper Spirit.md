# Reaper Spirit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Reaper Spirit | Undead | N/A | 40 + 10 for each spell level above 4th |  | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Reaping Scythe | 1d8 + 3 + summonSpellLevel necrotic | - | - |


**Multiattack.** The spirit makes a number of Reaping Scythe attacks equal to half the level of the spell (rounded down).

**Reaping Scythe.** {@atk mw} your spell attack modifier to hit (with advantage), reach 5 ft., the creature haunted by Haunt Creature. {@h}{@damage 1d8 + 3 + summonSpellLevel} necrotic damage.

^Tags: #monster #type_undead