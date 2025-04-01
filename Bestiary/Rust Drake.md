# Rust Drake

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Rust Drake | Dragon | 8 | 161 (19d8 + 76) | 17 | walk: 30 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d8 + 5 | 15 | - |
| Tail Swipe | 2d8 + 5 | - | - |
| Vomit Scrap {@recharge 5} | 5d8 + 5d8 | 15 | - |


**Multiattack.** The drake makes one Bite attack and two Tail Swipe attacks.

**Bite.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}18 ({@damage 3d8 + 5}) piercing damage, and the target must succeed on a {@dc 15} Constitution save or contract the rust drake lockjaw disease (see the Rust Drake Lockjaw trait).

**Tail Swipe.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d8 + 5}) bludgeoning damage.

**Vomit Scrap {@recharge 5}.** The rust drake vomits forth a 15-foot cone of rusted metal. Each creature in the area must make a {@dc 15} Dexterity saving throw, taking 22 ({@damage 5d8}) slashing damage and 22 ({@damage 5d8}) poison damage on a failed save, or half as much damage on a successful one. In addition, each creature that failed the saving throw must succeed on a {@dc 15} Constitution saving throw or contract the rust drake lockjaw disease (see the Rust Drake Lockjaw trait).

^Tags: #monster #type_dragon