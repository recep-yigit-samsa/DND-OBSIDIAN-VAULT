# Nosferatu

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Nosferatu | Undead | 8 | 85 (9d8 + 45) | 17 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 1d8 + 5 | - | - |
| Bite | 1d8 + 5 + 2d6 + 2d10 | - | - |
| Blood Disgorge {@recharge 5} | 4d8 | 16 | - |


**Multiattack.** The nosferatu makes two Claw attacks followed by one Bite attack. If both Claw attacks hit the same creature, the Bite attack is made with advantage.

**Claw.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d8 + 5}) slashing damage.

**Bite.** {@atk mw} {@hit 8} to hit, reach 5 ft., one creature. {@h}9 ({@damage 1d8 + 5}) piercing damage plus 7 ({@damage 2d6}) necrotic damage. If the target is missing any of its hit points, it instead takes 11 ({@damage 2d10}) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the nosferatu regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0. A Humanoid slain in this way and then buried in the ground rises as a nosferatu after {@dice 1d10} days.

**Blood Disgorge {@recharge 5}.** The nosferatu vomits blood in a 15-foot cone. Each creature in that area must make a {@dc 16} Constitution saving throw. On a failed save, a creature takes 18 ({@damage 4d8}) necrotic damage, and it can't regain hit points for 1 minute. On a successful save, the creature takes half as much damage with no additional effects.

^Tags: #monster #type_undead