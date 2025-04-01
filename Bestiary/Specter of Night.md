# Specter of Night

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Specter of Night | Undead | 12 | 142 (15d12 + 45) | 15 | walk: 60 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Hooves | 3d6 + 6 + 8d6 | 18 | - |
| Mournful Keening {@recharge} | - | 15 | - |
| Reaping Scythe | 1d12 + 6 + 8d6 | 15 | - |


**Multiattack.** The specter uses Mournful Keening if available, then makes one Hooves attack and one Reaping Scythe attack.

**Hooves.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}16 ({@damage 3d6 + 6}) bludgeoning damage plus 28 ({@damage 8d6}) necrotic damage. If the target is a Medium or smaller creature, it must succeed on a {@dc 18} Strength saving throw or have the {@condition prone} condition.

**Mournful Keening {@recharge}.** The specter utters a keening wail, calling to those close to death. Each non-Undead creature within 120 feet of the specter must make a {@dc 15} Constitution saving throw. On a failure, the creature hears the wail and is marked for death. A creature marked for death can't regain hit points, has disadvantage on death saving throws, and all attack rolls against it are made with advantage. This effect lasts for 1 minute or until the creature is targeted by a {@spell remove curse} spell or similar magic.

**Reaping Scythe.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}12 ({@damage 1d12 + 6}) slashing damage plus 28 ({@damage 8d6}) necrotic damage. If the target is a creature, it must succeed on a {@dc 15} Constitution saving throw or gain a level of {@condition exhaustion}.

^Tags: #monster #type_undead