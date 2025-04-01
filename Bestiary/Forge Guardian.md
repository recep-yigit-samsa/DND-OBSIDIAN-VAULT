# Forge Guardian

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Forge Guardian | Construct | 27 | 420 (24d20 + 168) | 24 | walk: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Runeblade | 4d12 + 10 | 23 | - |
| Kick | 2d12 + 10 | - | - |
| Bladestorm {@recharge 5} | - | - | - |


**Multiattack.** The guardian makes two melee attacks.

**Runeblade.** {@atk mw} {@hit 18} to hit, reach 15 ft., one target. {@h}36 ({@damage 4d12 + 10}) slashing damage, and the target must succeed on a {@dc 23} Constitution {@quickref saving throws|PHB|2|1|saving throw} or be {@condition blinded} until it deals damage to the guardian.

**Kick.** {@atk mw} {@hit 18} to hit, reach 10 ft., one target. {@h}23 ({@damage 2d12 + 10}) bludgeoning damage, and the target is pushed up to 15 feet away from the guardian and knocked {@condition prone}.

**Bladestorm {@recharge 5}.** The guardian makes a Runeblade attack against every creature within 15 feet of it. On a hit, a target is also pushed up to 15 feet away from the guardian and knocked {@condition prone}.

^Tags: #monster #type_construct