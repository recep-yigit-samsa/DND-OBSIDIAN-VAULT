# Borthak

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Borthak | Monstrosity | 15 | 200 (16d12 + 96) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 7 + 2d6 | - | - |
| Stomp | 1d8 + 7 | - | - |
| Noxious Regurgitation {@recharge 5} | 7d6 | 21 | - |


**Multiattack.** The borthak makes one Bite attack or uses Noxious Regurgitation if available, and it makes two Stomp attacks.

**Bite.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}16 ({@damage 2d8 + 7}) piercing damage plus 7 ({@damage 2d6}) acid damage.

**Stomp.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}11 ({@damage 1d8 + 7}) bludgeoning damage.

**Noxious Regurgitation {@recharge 5}.** The borthak spews acid at a creature it can see within 120 feet of itself. The target must make a {@dc 21} Constitution saving throw. On a failed save, the creature takes 24 ({@damage 7d6}) acid damage and has the {@condition poisoned} condition until the start of the borthak's next turn. On a successful save, the creature takes half as much damage only.

^Tags: #monster #type_monstrosity