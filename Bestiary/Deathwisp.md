# Deathwisp

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Deathwisp | Undead | 7 | 82 (11d8 + 33) | 15 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Ghostly Pike | 2d10 + 5 + 2d8 | - | - |
| Life Drain | 4d8 + 5 | 15 | - |
| Create Specter | - | - | - |


**Multiattack.** The deathwisp makes two Ghostly Pike attacks, or it can make one Ghostly Pike attack and one Life Drain attack.

**Ghostly Pike.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) force damage plus 9 ({@damage 2d8}) necrotic damage.

**Life Drain.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}23 ({@damage 4d8 + 5}) necrotic damage. The target must succeed on a {@dc 15} Constitution saving throw or its hp maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hp maximum to 0.

**Create Specter.** The deathwisp targets a Humanoid within 10 feet of it that has been dead for no longer than 1 minute and died violently. The target's spirit rises as a specter in the space of its corpse or in the nearest unoccupied space. This specter is under the deathwisp's control. The deathwisp can have no more than twelve specters under its control at one time.

^Tags: #monster #type_undead