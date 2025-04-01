# Wight

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Wight | Undead | 3 | 82 (11d8 + 33) | 14 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Necrotic Sword | 1d8 + 2 + 1d8 | - | - |
| Necrotic Bow | 1d8 + 2 + 1d8 | - | - |
| Life Drain | 1d8 + 2 | 13 | - |


**Multiattack.** The wight makes two attacks, using Necrotic Sword or Necrotic Bow in any combination. It can replace one attack with a use of Life Drain.

**Necrotic Sword.** {@atkr m} {@hit 4}, reach 5 ft. {@h}6 ({@damage 1d8 + 2}) Slashing damage plus 4 ({@damage 1d8}) Necrotic damage.

**Necrotic Bow.** {@atkr r} {@hit 4}, range 150/600 ft. {@h}6 ({@damage 1d8 + 2}) Piercing damage plus 4 ({@damage 1d8}) Necrotic damage.

**Life Drain.** {@actSave con} {@dc 13}, one creature within 5 feet. {@actSaveFail} 6 ({@damage 1d8 + 2}) Necrotic damage, and the target's {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by an amount equal to the damage taken. A Humanoid slain by this attack rises 24 hours later as a {@creature Zombie|XMM} under the wight's control, unless the Humanoid is restored to life or its body is destroyed. The wight can have no more than twelve zombies under its control at a time.

^Tags: #monster #type_undead