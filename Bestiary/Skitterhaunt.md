# Skitterhaunt

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Skitterhaunt | Ooze | 4 | 95 (10d10 + 40) | 14 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Mandibles | 1d4 + 2 + 2d8 | 12 | - |
| Sting | 1d8 + 2 + 2d8 | - | - |
| Infest Vermin | 2d6 | 14 | - |
| Acid Spray {@recharge} | 4d8 | 14 | - |


**Multiattack.** The skitterhaunt makes one Mandibles attack and one Sting attack, or it makes two Sting attacks.

**Mandibles.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}5 ({@damage 1d4 + 2}) slashing damage plus 9 ({@damage 2d8}) acid damage, and the target is {@condition grappled} (escape {@dc 12}) if it is a Medium or smaller creature. Until this grapple ends, the creature is {@condition restrained}, and the skitterhaunt can't use its Mandibles on another target.

**Sting.** {@atk mw} {@hit 4} to hit, reach 5 ft., one creature. {@h}6 ({@damage 1d8 + 2}) piercing damage plus 9 ({@damage 2d8}) acid damage.

**Infest Vermin.** The skitterhaunt infests a Large or smaller Beast with an exoskeleton within 5 feet of it. The target must succeed on a {@dc 14} Constitution saving throw or become {@condition poisoned} until the skitterhaunt no longer infests it. Every 24 hours that elapse, the target must repeat the saving throw or take 7 ({@damage 2d6}) acid damage, and its hp maximum is reduced by that amount. This reduction lasts until the target finishes a long rest after the skitterhaunt no longer infests it. The target dies if this reduces its hp maximum to 0. The skitterhaunt then takes control of the body, dissolving the flesh and hiding within the exoskeleton. A target that succeeds on two consecutive saving throws forces the skitterhaunt out of its body and is immune to the skitterhaunt's Infest Vermin for the next 24 hours.

**Acid Spray {@recharge}.** The skitterhaunt spits acid in a 30-foot line that is 5 feet wide. Each creature in that line must make a {@dc 14} Dexterity saving throw, taking 18 ({@damage 4d8}) acid damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_ooze