# Devourer

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Devourer | Fiend | 13 | 178 (17d10 + 85) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d6 + 5 + 6d6 | - | - |
| Imprison Soul | - | - | - |
| Soul Rend {@recharge} | 8d10 | 18 | - |


**Multiattack.** The devourer makes two claw attacks and can use either Imprison Soul or Soul Rend.

**Claw.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) slashing damage plus 21 ({@damage 6d6}) necrotic damage.

**Imprison Soul.** The devourer chooses a living humanoid with 0 hit points that it can see within 30 feet of it. That creature is teleported inside the devourer's ribcage and imprisoned there. A creature imprisoned in this manner has disadvantage on death saving throws. If it dies while imprisoned, the devourer regains 25 hit points, immediately recharges Soul Rend, and gains an additional action on its next turn. Additionally, at the start of its next turn, the devourer regurgitates the slain creature as a bonus action, and the creature becomes an undead. If the victim had 2 or fewer Hit Dice, it becomes a zombie. if it had 3 to 5 Hit Dice, it becomes a ghoul. Otherwise, it becomes a wight. A devourer can imprison only one creature at a time.

**Soul Rend {@recharge}.** The devourer creates a vortex of life-draining energy in a 20-foot radius centered on itself. Each humanoid in that area must make a {@dc 18} Constitution saving throw, taking 44 ({@damage 8d10}) necrotic damage on a failed save, or half as much damage on a successful one. Increase the damage by 10 for each living humanoid with 0 hit points in that area.

^Tags: #monster #type_fiend