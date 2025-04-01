# Deep Drake

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Deep Drake | Dragon | 9 | 150 (20d10 + 40) | 17 | walk: 40 ft., climb: 30 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 | - | - |
| Claw | 2d6 + 5 | - | - |
| Stinger | 2d10 + 5 + 2d6 + 2d6 | 16 | - |
| Enervating Breath {@recharge 5} | 10d6 | 16 | - |


**Multiattack.** The drake makes one Bite attack, two Claw attacks, and one Stinger attack.

**Bite.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage.

**Claw.** {@atk mw} {@hit 9} to hit, reach 5 ft, one target. {@h}12 ({@damage 2d6 + 5}) slashing damage.

**Stinger.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage plus 7 ({@damage 2d6}) poison damage, and the target must succeed on a {@dc 16} Constitution saving throw or become {@condition poisoned} for 1 minute. A {@condition poisoned} creature must repeat the saving throw at the end of each of its turns. On a failure, the creature takes 7 ({@damage 2d6}) poison damage. On a success, the condition ends. When animate dead is cast on one or more creatures killed by this poison, the spellcaster requires no material components and can cast the spell as an action.

**Enervating Breath {@recharge 5}.** The deep drake exhales pain-inducing, purple-black energy in a 90-foot line that is 5 feet wide. Each creature in the line must make a {@dc 16} Dexterity saving throw. On a failure, a creature takes 35 ({@damage 10d6}) necrotic damage and is {@condition stunned} until the end of its next turn. On a success, a creature takes half the damage and isn't {@condition stunned}.

^Tags: #monster #type_dragon