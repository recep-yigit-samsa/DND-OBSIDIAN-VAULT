# Aerosaur

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Aerosaur | Unknown | 10 | 155 (10d20 + 50) | 14 | walk: 20 ft., fly: 120 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d12 + 8 | 18 | - |
| Talons | 3d10 + 8 | - | - |
| Wing Gusts {@recharge 5} | 7d10 | 20 | - |


**Multiattack.** The aerosaur makes one Bite attack and one Talons attack.

**Bite.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}27 ({@damage 3d12 + 8}) piercing damage. If the target is a Huge or smaller creature, it has the {@condition grappled} condition (escape {@dc 18}). Until this grapple ends, the target has the {@condition restrained} condition, and the aerosaur can't Bite another target.

**Talons.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}24 ({@damage 3d10 + 8}) slashing damage.

**Wing Gusts {@recharge 5}.** The aerosaur beats its wings, creating bursts of thunderous force. Each creature within 10 feet of the aerosaur must make a {@dc 20} Strength saving throw. On a failed save, a creature takes 38 ({@damage 7d10}) thunder damage, is pushed up to 30 feet horizontally from the aerosaur, and has the {@condition prone} condition. On a successful save, a creature takes half as much damage and is pushed up to 15 feet horizontally from the aerosaur.

^Tags: #monster #type_unknown