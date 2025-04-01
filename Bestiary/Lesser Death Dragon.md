# Lesser Death Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Lesser Death Dragon | Undead | 10 | 199 (21d10 + 84) | 15 | walk: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 5 + 1d8 | - | - |
| Claw | 1d6 + 5 | 15 | - |
| Cataclysmic Breath {@recharge 5} | 8d8 | 16 | - |


**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}14 ({@damage 2d8 + 5}) piercing damage plus 4 ({@damage 1d8}) necrotic damage.

**Claw.** {@atk mw} {@hit 9} to hit, reach 5 ft. one target. {@h}8 ({@damage 1d6 + 5}) slashing damage. If the target is a Medium or smaller creature, it is {@condition grappled} (escape {@dc 15}). Until this grapple ends, the target is {@condition restrained}. The dragon has two claws, each of which can grapple one target.

**Cataclysmic Breath {@recharge 5}.** The dragon exhales a wave of ghostly purple flames in a 30-foot cone. Each creature in that area must make a {@dc 16} Dexterity saving throw, taking 36 ({@damage 8d8}) necrotic damage on a failed save, or half as much damage on a successful one. A creature dies if the breath reduces it to 0 hit points. Additionally, any Medium or smaller Humanoid killed by the breath's damage, as well as every corpse of such a creatures within the cone, becomes a zombie (see the Monster Manual) under the dragon's control. The zombie acts on the dragon's initiative but immediately after the dragon's turn. Absent any other command, the zombie tries to kill any non-Undead creature it encounters.

^Tags: #monster #type_undead