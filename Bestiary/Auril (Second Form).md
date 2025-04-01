# Auril (Second Form)

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Auril (Second Form) | Elemental | 10 | 136 (13d10 + 65) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Ice Morningstar | 1d8 + 3 + 2d8 | - | - |
| Ice Dart | 1d4 + 3 + 1d6 | - | - |
| Cone of Cold (Recharges after a Short or Long Rest) | 8d8 | 21 | - |
| Create Ice Mephit (3/Day) | - | - | - |
| Ice Stasis {@recharge 5} | 6d6 | 21 | - |


**Multiattack.** Auril attacks twice with her ice morningstar or hurls three ice darts.

**Ice Morningstar.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d8 + 3}) piercing damage plus 9 ({@damage 2d8}) cold damage.

**Ice Dart.** {@atk rw} {@hit 7} to hit, range 20/60 ft., one target. {@h}5 ({@damage 1d4 + 3}) piercing damage plus 3 ({@damage 1d6}) cold damage.

**Cone of Cold (Recharges after a Short or Long Rest).** Auril causes a magical blast of cold air to erupt from her hand. Each creature in a 60-foot cone must make a {@dc 21} Constitution saving throw, taking 36 ({@damage 8d8}) cold damage on a failed save, or half as much damage on a successful one.

**Create Ice Mephit (3/Day).** Auril breaks off an icicle from her body and hurls it into an unoccupied space she can see within 20 feet of her, where it magically transforms into an {@creature ice mephit} (see its entry in the Monster Manual). The mephit acts immediately after Auril in the initiative order and obeys her commands.

**Ice Stasis {@recharge 5}.** Auril magically creates a gem-sized ice crystal that hovers in a space within 5 feet of her. Auril then targets a creature she can see within 60 feet of the crystal. The target must succeed on a {@dc 21} Charisma saving throw or become trapped in the crystal, which is immovable. If the saving throw succeeds, the crystal shatters and nothing else happens. A creature trapped in the crystal is {@condition stunned}, has {@quickref Cover||3||total cover} against attacks and other effects outside the crystal, and takes 21 ({@damage 6d6}) cold damage at the start of each of its turns. The creature can repeat the saving throw at the end of each of its turns, freeing itself on a success. The creature is also freed if the crystal is destroyed, which is a Tiny object with AC 18, 9 hit points, and immunity to all damage except fire damage. The freed creature appears in an unoccupied space of its choice within 30 feet of the shattered crystal.

^Tags: #monster #type_elemental