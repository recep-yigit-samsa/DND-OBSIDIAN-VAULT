# Berstuc Demon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Berstuc Demon | Unknown | 11 | 157 (15d10 + 75) | 18 | walk: 40 ft., burrow: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 3d8 + 6 | 17 | - |
| Enclose | 6d6 | 15 | - |


**Multiattack.** The berstuc makes three Slam attacks. If two Slam attacks hit a Medium or smaller creature, the berstuc can use Enclose on it.

**Slam.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}19 ({@damage 3d8 + 6}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 17}) if it is a Large or smaller creature and the berstuc doesn't have two other creatures {@condition grappled}.

**Enclose.** The berstuc encloses a Medium or smaller creature {@condition grappled} by it in a mossy growth on the berstuc's body, and the grapple ends. While enclosed in the berstuc's growth, the target is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} from attacks and other effects outside the berstuc, and it takes 21 ({@damage 6d6}) poison damage at the start of each of the berstuc's turns. The berstuc can have only one creature enclosed at a time. If the berstuc takes 30 damage or more on a single turn from a creature inside its growth, the berstuc must succeed on a {@dc 15} Constitution saving throw at the end of that turn or expel the enclosed creature as the growth bursts. The expelled creature falls {@condition prone} in a space within 5 feet of the berstuc. If the berstuc dies, an enclosed creature is no longer {@condition restrained} by it and can escape from the growth by using 5 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_unknown