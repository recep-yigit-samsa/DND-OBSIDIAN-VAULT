# Hoard Mimic

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hoard Mimic | Monstrosity | 8 | 123 (13d12 + 39) | 14 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 + 2d6 | - | - |
| Pseudopod | 2d6 + 5 | 16 | - |
| Caustic Mist {@recharge 5} | 6d8 | 14 | - |
| Shapechanger | - | - | - |


**Multiattack.** The mimic makes one Bite attack and two Pseudopod attacks.

**Bite.** {@atk mw} {@hit 8} to hit, reach 5 ft., one creature. {@h}16 ({@damage 2d10 + 5}) piercing damage plus 7 ({@damage 2d6}) acid damage.

**Pseudopod.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d6 + 5}) bludgeoning damage, and the mimic adheres to the target. A creature adhered to the mimic is also {@condition grappled} by it (escape {@dc 16}). Until this grapple ends, the target is {@condition restrained}. Ability checks made to escape this grapple have disadvantage.

**Caustic Mist {@recharge 5}.** The mimic sprays a fine mist of acid in a 30-foot cone. Each creature in that area must make a {@dc 14} Dexterity saving throw. On a failed save, the creature takes 27 ({@damage 6d8}) acid damage and is {@condition blinded} until the end of its next turn. On a successful save, the creature takes half as much damage and isn't {@condition blinded}.

**Shapechanger.** The mimic transforms into a hoard or back into its true, amorphous form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

^Tags: #monster #type_monstrosity