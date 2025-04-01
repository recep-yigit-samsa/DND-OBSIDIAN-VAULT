# Bukavac

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Bukavac | Monstrosity | 9 | 199 (21d10 + 84) | 16 | walk: 40 ft., swim: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 | - | - |
| Claw | 1d12 + 5 | 16 | - |
| Gore | 3d10 + 5 | - | - |
| Croaking Blast {@recharge 5} | 8d8 | 16 | - |


**Multiattack.** The bukavac makes one Bite attack, one Gore attack, and two Claw attacks.

**Bite.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage.

**Claw.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}11 ({@damage 1d12 + 5}) slashing damage, and the target is {@condition grappled} (escape {@dc 16}) if it is a Medium or smaller creature. The bukavac can have no more than two creatures {@condition grappled} at a time.

**Gore.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}21 ({@damage 3d10 + 5}) piercing damage.

**Croaking Blast {@recharge 5}.** A bukavac can emit a howling thunderclap in a 15-foot radius. Each creature in that area must make a {@dc 16} Constitution saving throw. On a failure, a creature takes 36 ({@damage 8d8}) thunder damage and is {@condition deafened} until cured by the {@spell lesser restoration} spell or similar magic. On a success, a creature takes half the damage and isn't {@condition deafened}.

^Tags: #monster #type_monstrosity