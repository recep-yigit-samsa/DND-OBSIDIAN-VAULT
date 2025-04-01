# Greater Death Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Greater Death Dragon | Undead | 14 | 230 (20d12 + 100) | 16 | walk: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 6 + 1d8 | 19 | - |
| Claw | 1d8 + 6 | - | - |
| Cataclysmic Breath {@recharge 5} | 10d8 | 18 | - |


**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d10 + 6}) piercing damage plus 4 ({@damage 1d8}) necrotic damage. If the target is a Large or smaller creature, it is {@condition grappled} (escape {@dc 19}). Until this grapple ends, the target is {@condition restrained}, and the dragon can't bite a different target.

**Claw.** {@atk mw} {@hit 11} to hit, reach 5 ft. one target. {@h}10 ({@damage 1d8 + 6}) slashing damage.

**Cataclysmic Breath {@recharge 5}.** The dragon exhales a wave of ghostly purple flames in a 60-foot cone. Each creature in that area must make a {@dc 18} Dexterity saving throw, taking 45 ({@damage 10d8}) necrotic damage on a failed save, or half as much damage on a successful one. A creature dies if the breath reduces it to 0 hit points. Additionally, any Medium or smaller Humanoid killed by the breath's damage, as well as every corpse of such a creature within the cone, becomes a zombie (see the Monster Manual) under the dragon's control. The zombie acts on the dragon's initiative but immediately after the dragon's turn. Absent any other command, the zombie tries to kill any non-Undead creature it encounters.

^Tags: #monster #type_undead