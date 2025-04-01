# Darkweaver

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Darkweaver | Aberration | 10 | 149 (23d8 + 46) | 16 | walk: 50 ft., climb: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d6 + 3 + 5d6 | - | - |
| Shadow Web | 3d10 | 15 | - |
| Reel | - | - | - |


**Multiattack.** The darkweaver makes two Shadow Web attacks and one Bite attack. It can use Reel after any of these attacks.

**Bite.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}13 ({@damage 3d6 + 3}) piercing damage plus 17 ({@damage 5d6}) necrotic damage, and if the target is a creature, the target's hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

**Shadow Web.** {@atk rw} {@hit 7} to hit, reach 120 ft., one creature. {@h}16 ({@damage 3d10}) necrotic damage, and the target has the {@condition grappled} condition (escape {@dc 15}). The shadow web can be attacked and destroyed (AC 16; 20 hit points; vulnerability to radiant damage; immunity to bludgeoning, necrotic, poison, and psychic damage). The darkweaver can grapple up to six creatures at a time using its shadow web.

**Reel.** The darkweaver pulls each creature it has {@condition grappled} up to 60 feet toward itself.

^Tags: #monster #type_aberration