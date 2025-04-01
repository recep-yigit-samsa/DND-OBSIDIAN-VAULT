# Mage Hunter Golem

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mage Hunter Golem | Construct | 15 | 243 (18d10 + 144) | 20 | walk: 30 ft., fly: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 3d8 + 7 | - | - |
| Claw {@recharge 5} | 1d8 + 7 | 16 | - |
| Antimagic Jolt | 6d6 | 18 | - |


**Multiattack.** The golem uses its Antimagic Jolt and makes two melee attacks, or it makes three melee attacks.

**Slam.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}20 ({@damage 3d8 + 7}) bludgeoning damage.

**Claw {@recharge 5}.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}11 ({@damage 1d8 + 7}) bludgeoning damage, and the target must succeed on a {@dc 16} Dexterity {@quickref saving throws|PHB|2|1|saving throw} or have a magic collar placed upon its neck. While the target wears the collar, it is magically prevented from speaking and cannot cast any spell. A successful {@dc 25} Dexterity check using {@item thieves' tools|PHB} removes the collar.

**Antimagic Jolt.** Each creature within the golem's Antimagic Cone that has the ability to cast a spell of 1st level or higher must make a {@dc 18} Wisdom {@quickref saving throws|PHB|2|1|saving throw}, taking 21 ({@damage 6d6}) psychic damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct