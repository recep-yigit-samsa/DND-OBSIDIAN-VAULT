# Wraith

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Wraith | Undead | 5 | 67 (9d8 + 27) | 13 | walk: 5 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Life Drain | 4d8 + 3 | - | - |
| Create Specter | - | - | - |


**Life Drain.** {@atkr m} {@hit 6}, reach 5 ft. {@h}21 ({@damage 4d8 + 3}) Necrotic damage. If the target is a creature, its {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by an amount equal to the damage taken.

**Create Specter.** The wraith targets a Humanoid corpse within 10 feet of itself that has been dead for no longer than 1 minute. The target's spirit rises as a {@creature Specter|XMM} in the space of its corpse or in the nearest unoccupied space. The specter is under the wraith's control. The wraith can have no more than seven specters under its control at a time.

^Tags: #monster #type_undead