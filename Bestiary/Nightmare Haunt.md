# Nightmare Haunt

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Nightmare Haunt | Aberration | 5 | 44 (8d8 + 8) | 13 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 1d6 + 3 + 2d8 | - | - |
| Tendrils of Slumber {@recharge 5} | 2d10 | 14 | - |


**Multiattack.** The nightmare haunt makes two Claw attacks.

**Claw.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d6 + 3}) slashing damage plus 9 ({@damage 2d8}) psychic damage.

**Tendrils of Slumber {@recharge 5}.** The nightmare haunt creates spectral tendrils that cover the ground in a 20-foot square that it can see within 30 feet of itself for 1 minute or until it uses this action again. When a creature other than the nightmare haunt enters the affected area for the first time or starts its turn there, the creature must succeed on a {@dc 14} Strength saving throw or take 11 ({@damage 2d10}) necrotic damage and have the {@condition restrained} condition. The affected ground is also considered difficult terrain for creatures other than the nightmare haunt for the duration of its effect. A creature that starts its turn in the area and is already {@condition restrained} by the tendrils must repeat the saving throw. On a failed save, it has the {@condition unconscious} condition and instead of the {@condition restrained} condition caused by the tendrils. On a successful save, the effect ends on the creature. An {@condition unconscious} creature remains asleep until it is no longer in the area with tendrils, takes any damage, or is targeted by a {@spell remove curse} spell or similar magic.

^Tags: #monster #type_aberration