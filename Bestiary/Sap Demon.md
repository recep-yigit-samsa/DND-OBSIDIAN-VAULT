# Sap Demon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sap Demon | Ooze | 4 | 81 (18d6 + 18) | 13 | walk: 20 ft., climb: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 12 | - |
| Slam | 2d4 + 2 + 2d6 | - | - |
| Lob Sap | 3d6 + 2 | - | - |
| Soul Sap {@recharge} | 1d4 | 12 | - |


**Multiattack.** The sap demon makes two Slam or Lob Sap attacks. If both Slam attacks hit a Medium or smaller creature, the creature is {@condition grappled} (escape {@dc 12}).

**Slam.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}7 ({@damage 2d4 + 2}) bludgeoning damage plus 7 ({@damage 2d6}) acid damage.

**Lob Sap.** {@atk rw} {@hit 4} to hit, range 20/60 ft., one target. {@h}12 ({@damage 3d6 + 2}) bludgeoning damage, and the target's speed is reduced by 10 feet until the end of its next turn.

**Soul Sap {@recharge}.** One humanoid the sap demon is grappling or that is {@condition incapacitated} within 5 feet of the sap demon must succeed on a {@dc 12} Constitution saving throw or be possessed by the sap demon. The sap demon then disappears, and the target is {@condition incapacitated} and loses control of its body. The sap demon now controls the body but doesn't deprive the target of awareness. The ooze can't be targeted by any attack, spell, or other effect, except ones that restore a creature's hp maximum. The ooze retains its Intelligence, Wisdom, and Charisma and condition immunities. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies. While possessed, the target's body seeps blood out of its ears, nose, and eyes, and the target takes 2 ({@damage 1d4}) acid damage at the end of each hour. Its hp maximum is also reduced by that amount. This reduction lasts until the target finishes a long rest after the possession ends. The possession lasts until the body drops to 0 hp, the ooze ends it as a bonus action, or the ooze is forced out by an effect like the {@spell greater restoration} spell. When the possession ends, the ooze reappears in an unoccupied space within 5 feet of the body. The target is immune to this sap demon's Soul Sap for 24 hours after succeeding on the saving throw or after the possession ends.

^Tags: #monster #type_ooze