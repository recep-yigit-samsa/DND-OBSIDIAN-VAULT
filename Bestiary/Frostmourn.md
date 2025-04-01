# Frostmourn

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Frostmourn | Undead | 10 | 195 (17d12 + 85) | 13 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Freezing Touch | 4d8 + 4d8 | - | No Damage ❌ |
| Icy Axe | 3d8 + 6 + 2d6 | - | - |
| Polar Ray | 5d10 + 4 | - | - |


**Multiattack.** The frostmourn makes one Freezing Touch attack and one Icy Axe attack. It can replace one of these attacks with a Polar Ray attack.

**Freezing Touch.** {@atk mw} {@hit 10} to hit, reach 5 ft., one creature. {@h}18 ({@damage 4d8}) cold damage plus 18 ({@damage 4d8}) necrotic damage. If this damage would reduce the target to 0 hit points, the target drops to 1 hit point instead and has the {@condition petrified} condition, turning into a frozen statue. If the statue takes bludgeoning damage, it shatters, killing the frozen creature. If the statue would take fire damage, it instead takes no damage and thaws, ending the petrification.

**Icy Axe.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}19 ({@damage 3d8 + 6}) slashing damage plus 7 ({@damage 2d6}) cold damage.

**Polar Ray.** {@atk rs} {@hit 8} to hit, range 120 ft., one target. {@h}31 ({@damage 5d10 + 4}) cold damage, and the target's speed is reduced by 10 feet until the end of its next turn.

^Tags: #monster #type_undead