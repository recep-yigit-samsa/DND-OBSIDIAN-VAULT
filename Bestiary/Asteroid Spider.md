# Asteroid Spider

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Asteroid Spider | Monstrosity | 15 | 348 (24d20 + 96) | 17 | walk: 60 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d8 + 8 + 3d6 | - | - |
| Web Strand | - | 18 | - |
| Reel | - | - | - |


**Multiattack.** The spider makes two Web Strand attacks, uses Reel, and makes two Bite attacks.

**Bite.** {@atk mw} {@hit 13} to hit, reach 10 ft., one target. {@h}21 ({@damage 3d8 + 8}) piercing damage plus 10 ({@damage 3d6}) acid damage.

**Web Strand.** {@atk rw} {@hit 13} to hit, reach 120 ft., one creature. {@h}The target is {@condition grappled} (escape {@dc 18}). The web strand can be attacked and destroyed (AC 12; 20 hit points; vulnerability to fire damage; immunity to bludgeoning, poison, and psychic damage). The spider can grapple up to six creatures at a time using its web strands.

**Reel.** The spider pulls each creature {@condition grappled} by it up to 60 feet straight toward itself.

^Tags: #monster #type_monstrosity