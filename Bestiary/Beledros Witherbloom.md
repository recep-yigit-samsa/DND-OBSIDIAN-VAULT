# Beledros Witherbloom

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Beledros Witherbloom | Unknown | 24 | 444 (24d20 + 192) | 22 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d10 + 9 + 1d12 | - | - |
| Claw | 1d6 + 9 | - | - |
| Decaying Breath {@recharge 5} | 6d12 + 6d12 | 23 | - |
| Miasmal Flow | 1d10 | 23 | - |


**Multiattack.** Beledros makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 16} to hit, reach 15 ft., one target. {@h}14 ({@damage 1d10 + 9}) piercing damage plus 6 ({@damage 1d12}) necrotic damage.

**Claw.** {@atk mw} {@hit 16} to hit, reach 10 ft., one target. {@h}12 ({@damage 1d6 + 9}) slashing damage. If the target is a Huge or smaller creature, it is knocked {@condition prone}.

**Decaying Breath {@recharge 5}.** Beledros exhales decaying energy in a 90-foot cone. Each creature in that area must make a {@dc 23} Constitution saving throw, taking 39 ({@damage 6d12}) necrotic damage and 39 ({@damage 6d12}) poison damage on a failed save, or half as much damage on a successful one. A creature that takes damage from the breath can't regain hit points until the start of Beledros's next turn.

**Miasmal Flow.** Beledros becomes a swirling cloud of green mist and can move up to half her flying speed without provoking opportunity attacks, then resumes her true form. During this movement, she can move through creatures and objects as if they were {@quickref difficult terrain||3}. If she moves through a creature, it must succeed on a {@dc 23} Constitution saving throw or become {@condition poisoned} until the end of its next turn. If Beledros ends this move inside an object, she takes 5 ({@damage 1d10}) force damage and is shunted to the nearest unoccupied space.

^Tags: #monster #type_unknown