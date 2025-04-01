# Ice Maiden

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ice Maiden | Fey | 6 | 84 (13d8 + 26) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Ice Blade | 1d8 + 3 + 4d6 | - | - |
| Ice Bolt | 4d6 + 5 | - | - |
| Kiss of the Frozen Heart | - | 16 | - |
| Icy Embrace {@recharge 5} | 8d6 | 16 | - |


**Multiattack.** The ice maiden makes two Ice Blade or Ice Bolt attacks.

**Ice Blade.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d8 + 3}) slashing damage plus 14 ({@damage 4d6}) cold damage.

**Ice Bolt.** {@atk rs} {@hit 8} to hit, range 60 ft., one target. {@h}19 ({@damage 4d6 + 5}) cold damage.

**Kiss of the Frozen Heart.** The ice maiden kisses a willing Humanoid, freezing the target's heart. The target has immunity to cold damage, but it is {@condition charmed} by the ice maiden until the maiden ends the effect (no action required) or until the target is kissed by a creature that loves it. The {@condition charmed} target obeys the maiden's verbal commands. If the target suffers any harm from the maiden or her allies, or if it receives a suicidal command, it can make a {@dc 16} Wisdom saving throw, ending the effect on itself on a success. The maiden can have no more than three Humanoids {@condition charmed} at a time.

**Icy Embrace {@recharge 5}.** The ice maiden blasts wintry weather on a point she can see within 60 feet of her. Each creature within 15 feet of that point must make a {@dc 16} Dexterity saving throw. On a failure, a creature takes 28 ({@damage 8d6}) cold damage and is {@condition restrained} by ice until the end of its next turn. On a success, a creature takes half the damage and isn't {@condition restrained}. The area then becomes icy, difficult terrain for 1 minute.

^Tags: #monster #type_fey