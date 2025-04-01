# Ravenala

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ravenala | Plant | 5 | 126 (12d10 + 60) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 14 | - |
| Slam | 3d8 + 5 | - | - |
| Bursting Pod | 2d6 + 5 + 2d4 | 15 | - |
| Lamenting Engulfment | - | 14 | - |
| Healing Leaves (3/Day) | - | - | - |
| Encourage Growth (3/Day) | - | - | - |


**Multiattack.** The ravenala makes two Bursting Pod or Slam attacks. If both Slam attacks hit a Medium or smaller creature, the target is {@condition grappled} (escape {@dc 14}), and the ravenala uses its Lamenting Engulfment on the target.

**Slam.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}18 ({@damage 3d8 + 5}) bludgeoning damage.

**Bursting Pod.** {@atk rw} {@hit 8} to hit, range 30/120 ft., one target. {@h}12 ({@damage 2d6 + 5}) bludgeoning damage, and each creature within 5 feet of the target, including the target, must make a {@dc 15} Dexterity saving throw, taking 5 ({@damage 2d4}) piercing damage on a failed save, or half as much damage on a successful one.

**Lamenting Engulfment.** The ravenala engulfs a Medium or smaller creature {@condition grappled} by it. The engulfed target is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the ravenala, and it must succeed on a {@dc 14} Charisma saving throw at the start of each of the ravenala's turns or sing a lament of the mistakes and misdeeds it has performed in its lifetime. While singing, the engulfed creature can still act, but it can't otherwise speak, including casting spells with verbal components. If the ravenala moves, the engulfed creature moves with it. The ravenala can have only one creature engulfed at a time.

**Healing Leaves (3/Day).** The ravenala removes a leaf from its head and wraps the leaf around the wounds of one creature it can see within 5 feet of it. The target magically regains 10 {@dice 3d6} hp and is freed from any disease, poison, blindness, or deafness.

**Encourage Growth (3/Day).** The ravenala whispers magical words of growth to nonmagical plants on a point it can see within 30 feet of it. The plants burst with life and spread rapidly. The area within 20 feet of that point becomes difficult terrain for 24 hours.

^Tags: #monster #type_plant