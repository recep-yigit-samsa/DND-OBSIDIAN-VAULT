# Spark

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Spark | Elemental | 7 | 104 (16d4 + 64) | 15 | walk: 10 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Electric Touch | 3d8 + 3 | - | - |
| Inhabit | 2d6 | 14 | - |


**Multiattack.** The spark makes three Electric Touch attacks.

**Electric Touch.** {@atk ms} {@hit 6} to hit, reach 5 ft., one target. {@h}16 ({@damage 3d8 + 3}) lightning damage.

**Inhabit.** One Humanoid that the spark can see within 5 feet of it must succeed on a {@dc 14} Charisma saving throw or be inhabited by the spark. The spark then disappears, fusing with the target's nervous system, and the target is {@condition incapacitated} and loses control of its body. The spark now controls the body but doesn't deprive the target of awareness. The spark can't be targeted by any attack, spell, or other effect, and it retains its alignment, Intelligence, Wisdom, Charisma, immunity to being {@condition paralyzed}, {@condition petrified}, or {@condition unconscious}, and its Electric Touch attack. It otherwise uses the inhabited target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies. Every 24 hours that elapse, the target must succeed on a {@dc 14} Constitution saving throw or take 7 ({@damage 2d6}) lightning damage, and its hp maximum is reduced by that amount. This reduction lasts until the target finishes a long rest after the spark no longer inhabits it. The target dies if this reduces its hp maximum to 0. Each time the spark makes an Electric Touch attack and at the end of each long rest, the target can make a {@dc 14} Charisma saving throw, expelling the spark on a success. Alternatively, the spark can exit the target's body as a bonus action or can be forced out by an effect like the {@spell protection from energy} spell. The target is immune to this spark's Inhabit for 24 hours after succeeding on the saving throw or after the spark is expelled. A willing target retains full function of its body, doesn't need to make a Constitution saving throw every 24 hours, has immunity to lightning damage, and can communicate with the spark telepathically. If the spark inhabits a willing target, it takes its turn at the same time as the target, but the spark can attack only as a reaction to a creature moving within 5 feet of the target or as a reaction to the target attacking a creature within 5 feet of it.

^Tags: #monster #type_elemental