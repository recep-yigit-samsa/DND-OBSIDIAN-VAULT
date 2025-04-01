# Rust Monster

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Rust Monster | Monstrosity | 1/2 | 33 (6d8 + 6) | 14 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d8 + 1 | - | - |
| Antennae | - | 11 | - |
| Destroy Metal | - | - | - |


**Multiattack.** The rust monster makes one Bite attack and uses Antennae twice.

**Bite.** {@atkr m} {@hit 3}, reach 5 ft. {@h}5 ({@damage 1d8 + 1}) Piercing damage.

**Antennae.** The rust monster targets one nonmagical metal object—armor or a weapon—worn or carried by a creature within 5 feet of itself. {@actSave dex} {@dc 11}, the creature with the object. {@actSaveFail} The object takes a -1 penalty to the AC it offers (armor) or to its attack rolls (weapon). Armor is destroyed if the penalty reduces its AC to 10, and a weapon is destroyed if its penalty reaches -5. The penalty can be removed by casting the {@spell Mending|XPHB} spell on the armor or weapon.

**Destroy Metal.** The rust monster touches a nonmagical metal object within 5 feet of itself that isn't being worn or carried. The touch destroys a 1-foot {@variantrule Cube [Area of Effect]|XPHB|Cube} of the object.

^Tags: #monster #type_monstrosity