# Millitaur

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Millitaur | Monstrosity | 3 | 85 (10d10 + 30) | 14 | walk: 40 ft., burrow: 20 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Handaxe | 2d6 + 3 + 1d6 | - | - |
| Poisonous Flask {@recharge 5} | 4d6 | 13 | - |
| Healing Tonic (2/Day) | - | - | - |


**Multiattack.** The millitaur makes two Handaxe attacks.

**Handaxe.** {@atk mw,rw} {@hit 5} to hit, reach 5 ft. or range 20/60 ft., one target. {@h}10 ({@damage 2d6 + 3}) slashing damage plus 3 ({@damage 1d6}) poison damage.

**Poisonous Flask {@recharge 5}.** The millitaur hastily combines alchemical substances into a poisonous concoction and throws it at a point the millitaur can see within 30 feet. Each creature within 15 feet of that point must make a {@dc 13} Dexterity saving throw. On a failure, a creature takes 14 ({@damage 4d6}) poison damage and is {@condition poisoned} for 1 minute. On a success, a creature takes half the damage and isn't {@condition poisoned}. A {@condition poisoned} creature can make a {@dc 13} Constitution saving throw at the end of each of its turns, ending the effect on itself on a success.

**Healing Tonic (2/Day).** The millitaur administers a healing tonic to a willing creature within 5 feet of it. The target magically regains 7 {@dice 2d6} hp and is freed from any disease or poison.

^Tags: #monster #type_monstrosity