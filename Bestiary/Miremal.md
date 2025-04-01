# Miremal

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Miremal | Fey | 1/2 | 22 (5d6 + 5) | 12 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 2 | - | - |
| Claw | 1d4 + 2 | - | - |
| Bog Spew {@recharge 5} | 2d6 | 11 | - |


**Multiattack.** The miremal makes one Bite attack and one Claw attack.

**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage.

**Claw.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}4 ({@damage 1d4 + 2}) slashing damage.

**Bog Spew {@recharge 5}.** The miremal spews a noxious stream of bog filth mixed with stomach acid at one creature it can see within 20 feet of it. The target must make a {@dc 11} Constitution saving throw. On a failure, the target takes 7 ({@damage 2d6}) acid damage and is {@condition blinded} until the end of its next turn. On a success, the target takes half the damage and isn't {@condition blinded}.

^Tags: #monster #type_fey