# Shoggoth

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Shoggoth | Aberration | 19 | 325 (21d12 + 189) | 18 | walk: 50 ft., climb: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 4d10 + 8 | 18 | - |
| Crush | 4d10 + 8 | 19 | - |


**Multiattack.** The shoggoth makes four Slam attacks. It can replace two Slam attacks with a use of Crush.

**Slam.** {@atk mw} {@hit 14} to hit, reach 15 ft., one target. {@h}30 ({@damage 4d10 + 8}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 18}) if it is a Large or smaller creature.

**Crush.** The shoggoth crushes up to two creatures it is grappling by rolling them beneath its bulk. Each target must succeed on a {@dc 19} Strength saving throw or take 30 ({@damage 4d10 + 8}) bludgeoning damage, be unable to breathe, and be {@condition restrained} until the grapple ends. If the shoggoth moves, a creature beneath it is no longer {@condition restrained} and is able to breathe, but it remains {@condition grappled}.

^Tags: #monster #type_aberration