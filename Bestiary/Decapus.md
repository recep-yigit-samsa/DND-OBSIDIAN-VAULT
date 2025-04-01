# Decapus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Decapus | Monstrosity | 4 | 75 (10d10 + 20) | 14 | walk: 15 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d4 + 2 | - | - |
| Tentacles | 9d4 + 2 + 5d4 + 2 | 14 | - |


**Multiattack.** The decapus makes two attacks: one with its bite and one with its tentacles.

**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one creature {@condition grappled} by the decapus. {@h}7 ({@damage 2d4 + 2}) piercing damage.

**Tentacles.** {@atk mw} {@hit 4} to hit, reach 10 ft., one target. {@h}24 ({@damage 9d4 + 2}) bludgeoning damage or 14 ({@damage 5d4 + 2}) bludgeoning damage if the decapus is grappling a creature other than the target or if the decapus is on the ground or floor. The target is also {@condition grappled} (escape {@dc 14}) unless the decapus is already grappling a creature. Until this grapple ends, the target is {@condition restrained}.

^Tags: #monster #type_monstrosity