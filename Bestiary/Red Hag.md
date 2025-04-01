# Red Hag

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Red Hag | Fey | 7 | 136 (16d8 + 64) | 15 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d8 + 4 + 2d8 | - | - |
| Blood Bolt | 2d8 + 5 | 16 | - |
| Siphon Blood {@recharge 5} | 10d6 | 16 | - |


**Multiattack.** The hag makes two Claw attacks or three Blood Bolt attacks. She can replace one attack with a use of Spellcasting.

**Claw.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) slashing damage plus 9 ({@damage 2d8}) necrotic damage.

**Blood Bolt.** {@atk rs} {@hit 8} to hit, range 60 ft., one target. {@h}14 ({@damage 2d8 + 5}) necrotic damage. If the target is a creature with blood, it must succeed on a {@dc 16} Constitution saving throw or be {@condition poisoned} until the end of its next turn.

**Siphon Blood {@recharge 5}.** The red hag drains blood from nearby creatures. Each creature that isn't a Construct or Undead within 20 feet of the red hag must make a {@dc 16} Constitution saving throw, taking 35 ({@damage 10d6}) necrotic damage on a failed save, or half as much damage on a successful one. If at least one creature fails the saving throw, the next spell the red hag casts is cast as if the spell used a spell slot two levels higher than the spell's lowest level.

^Tags: #monster #type_fey