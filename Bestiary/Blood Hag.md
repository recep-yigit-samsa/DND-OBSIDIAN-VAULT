# Blood Hag

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Blood Hag | Fey | 11 | 204 (24d8 + 96) | 16 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claws | 4d6 + 5 | 17 | - |
| Blood Bolt | 3d8 + 5 | 17 | - |
| Blood-Drinking Hair | 4d8 | 17 | - |
| Face Peel | 4d6 | 17 | - |
| Sanguine Curse | 2d8 | 17 | - |


**Multiattack.** The blood hag makes three Claw or Blood Bolt attacks and can use Blood-Drinking Hair or Face Peel. She can replace one attack with a use of Sanguine Curse.

**Claws.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}19 ({@damage 4d6 + 5}) slashing damage, and the target is {@condition grappled} (escape {@dc 17}) if it is a Medium or smaller creature. The blood hag has two claws, each of which can grapple only one target.

**Blood Bolt.** {@atk rs} {@hit 9} to hit, range 60 ft., one target. {@h}18 ({@damage 3d8 + 5}) necrotic damage. If the target is a creature with blood, it must succeed on a {@dc 17} Constitution saving throw or be {@condition poisoned} until the end of its next turn.

**Blood-Drinking Hair.** The hag drains blood from one creature {@condition grappled} by her. The target must make a {@dc 17} Constitution saving throw, taking 18 ({@damage 4d8}) necrotic damage on a failed save, or half as much damage on a successful one. The blood hag regains hp equal to half the necrotic damage taken.

**Face Peel.** The blood hag peels the face off one creature {@condition grappled} by her. The target must succeed on a {@dc 17} Dexterity saving throw or take 14 ({@damage 4d6}) slashing damage and be {@condition stunned} until the end of its next turn. The target's hp maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. While its hp maximum is reduced in this way, the target has disadvantage on all Charisma checks. The target dies if this effect reduces its hp maximum to 0.

**Sanguine Curse.** The blood hag curses one creature she can see or sense within 60 feet of her. The target must succeed on a {@dc 17} Wisdom saving throw or be cursed for 1 minute. A creature automatically succeeds on this saving throw if it doesn't have blood. While cursed, the target is {@condition incapacitated} and takes 9 ({@damage 2d8}) necrotic damage at the start of each of its turns as its internal blood vessels rupture. The cursed target can repeat the saving throw at the end of each of its turns, ending the curse on itself on a success. The blood hag can have only one target cursed at a time. If it curses another, the effect on the previous target ends.

^Tags: #monster #type_fey