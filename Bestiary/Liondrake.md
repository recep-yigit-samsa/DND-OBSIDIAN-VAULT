# Liondrake

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Liondrake | Monstrosity | 7 | 119 (14d10 + 42) | 16 | walk: 40 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 4 | 15 | - |
| Claw | 2d6 + 4 | - | - |
| Blood-Chilling Roar {@recharge 4} | - | 14 | - |


**Multiattack.** The liondrake makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage. If the target is a Medium or smaller creature, it must succeed on a {@dc 15} Strength saving throw or be knocked {@condition prone}.

**Claw.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) slashing damage.

**Blood-Chilling Roar {@recharge 4}.** The liondrake lets out a terrifying roar audible out to 300 feet. Any creature within 30 feet of the liondrake that can hear its roar must succeed on a {@dc 14} Wisdom saving throw or be {@condition frightened} of the liondrake for 1 minute. A creature that fails the save by 5 or more is also {@condition paralyzed} for the same duration. A creature can repeat the saving throw at the end of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to this liondrake's Blood-Chilling Roar for the next 24 hours.

^Tags: #monster #type_monstrosity