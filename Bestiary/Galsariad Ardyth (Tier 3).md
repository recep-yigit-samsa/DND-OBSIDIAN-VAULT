# Galsariad Ardyth (Tier 3)

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Galsariad Ardyth (Tier 3) | Unknown | 8 | 90 (20d8) | 17 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., swim: {'number': 40, 'condition': '(ring of swimming)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Drain Potential | 4d10 | - | - |
| Ruidium Dagger | 1d4 + 2 + 2d6 | - | - |
| Gravity Wave {@recharge 5} | 12d6 | 16 | - |


**Multiattack.** Galsariad makes one Drain Potential attack and one Ruidium Dagger attack.

**Drain Potential.** {@atk ms,rs} {@hit 8} to hit, reach 5 ft. or range 120 ft., one creature. {@h}22 ({@damage 4d10}) necrotic damage, and Galsariad gains 10 temporary hit points.

**Ruidium Dagger.** {@atk mw,rw} {@hit 5} to hit, reach 5 ft. or range 20/60 ft., one target. {@h}4 ({@damage 1d4 + 2}) piercing damage plus 7 ({@damage 2d6}) psychic damage.

**Gravity Wave {@recharge 5}.** Galsariad causes a rippling wave of magical gravity to fill a 30-foot-radius sphere centered on a point he can see within 100 feet of himself. Each creature in that area must make a {@dc 16} Strength saving throw. On a failed saving throw, the creature takes 42 ({@damage 12d6}) force damage and is {@condition restrained} for 1 minute. On a successful save, the creature takes half as much damage and isn't {@condition restrained}. A {@condition restrained} creature can repeat the save at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_unknown