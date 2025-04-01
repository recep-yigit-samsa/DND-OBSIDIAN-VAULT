# Dybbuk

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dybbuk | Unknown | 4 | 37 (5d8 + 15) | 14 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Tendril | 2d8 + 4 | - | - |
| Possess Corpse {@recharge} | - | - | - |


**Tendril.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) necrotic damage. If the target is a creature, its hit point maximum is also reduced by 3 ({@dice 1d6}). This reduction lasts until the target finishes a short or long rest. The target dies if this effect reduces its hit point maximum to 0.

**Possess Corpse {@recharge}.** The dybbuk disappears into an intact corpse it can see within 5 feet of it. The corpse must be Large or smaller and be that of a beast or a humanoid. The dybbuk is now effectively the possessed creature. Its type becomes undead, though it now looks alive, and it gains a number of temporary hit points equal to the corpse's hit point maximum in life. While possessing the corpse, the dybbuk retains its hit points, alignment, Intelligence, Wisdom, Charisma, telepathy, and immunity to poison damage, {@condition exhaustion}, and being {@condition charmed} and {@condition frightened}. It otherwise uses the possessed target's game statistics, gaining access to its knowledge and proficiencies but not its class features, if any. The possession lasts until the temporary hit points are lost (at which point the body becomes a corpse once more) or the dybbuk ends its possession using a bonus action. When the possession ends, the dybbuk reappears in an unoccupied space within 5 feet of the corpse.

^Tags: #monster #type_unknown