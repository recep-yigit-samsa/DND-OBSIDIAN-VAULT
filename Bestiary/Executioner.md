# Executioner

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Executioner | Construct | 20 | 405 (30d12 + 210) | 20 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Guillotine Blade | 6d6 + 9 + 4d6 | 21 | - |
| Necrotic Vents {@recharge 5} | 10d8 | 21 | - |


**Guillotine Blade.** {@atk mw,rw} {@hit 15} to hit, reach 10 ft., or range 30/120 ft., one target. {@h}30 ({@damage 6d6 + 9}) slashing damage plus 14 ({@damage 4d6}) necrotic damage. The target must succeed on a {@dc 21} Constitution saving throw or its hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the creature finishes a long rest. The target dies if this effect reduces its hit point maximum to 0. Immediately after making a ranged attack, this weapon flies back to the Executioner's hands.

**Necrotic Vents {@recharge 5}.** The Executioner vents necrotic gas in a 30-foot radius. Each creature in that area must succeed on a {@dc 21} Constitution saving throw, taking 45 ({@damage 10d8}) necrotic damage on a failed save, or half as much damage on a successful one. A creature who fails this saving throw by 5 or more gains one {@adventure level of contamination|DoDk|12}.

^Tags: #monster #type_construct