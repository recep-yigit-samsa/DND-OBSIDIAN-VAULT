# Ember

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ember | Unknown | 22 | 270 (20d12 + 140) | 20 | walk: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 15 + 2d6 + 6 | - | - |
| Claw | 2d6 + 15 | - | - |
| Firestorm Breath {@recharge 5} | 16d6 | 22 | - |


**Multiattack.** Ember makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 16} to hit, reach 10 ft., one target. {@h}26 ({@damage 2d10 + 15}) piercing damage plus 13 ({@damage 2d6 + 6}) fire damage.

**Claw.** {@atk mw} {@hit 16} to hit, reach 5 ft., one target. {@h}22 ({@damage 2d6 + 15}) slashing damage.

**Firestorm Breath {@recharge 5}.** Ember exhales roiling flames and ash in a 90-foot cone. Each creature in that area must make a {@dc 22} Dexterity saving throw. On a failed save, a creature takes 56 ({@damage 16d6}) fire damage and is pushed up to 30 feet away from Ember and knocked {@condition prone}. On a successful save, a creature takes half as much damage with no other effects. If a creature is reduced to 0 hit points by this effect, the creature immediately dies, and its body is reduced to ash.

^Tags: #monster #type_unknown