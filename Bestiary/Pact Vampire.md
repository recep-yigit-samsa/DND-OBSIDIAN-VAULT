# Pact Vampire

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Pact Vampire | Undead | 15 | 178 (17d8 + 102) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d6 + 6 + 3d8 | - | - |
| Call Blood | 4d10 | 18 | - |
| Charm | - | 18 | - |
| Children of the Lower Planes (1/Day) | - | - | - |


**Multiattack.** The pact vampire makes three Claw attacks.

**Claw.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage plus 13 ({@damage 3d8}) poison damage.

**Call Blood.** The pact vampire draws the blood out of a bleeding creature's body, where it flows through the air into the vampire's mouth. One creature the vampire can see within 60 feet of it that doesn't have all its hp and isn't a Construct or Undead must succeed on a {@dc 18} Constitution saving throw or take 22 ({@damage 4d10}) necrotic damage, and its hp maximum is reduced by that amount. The vampire regains hp equal to half the damage dealt. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hp maximum to 0.

**Charm.** One Humanoid the vampire can see within 30 feet of it must succeed on a {@dc 18} Wisdom saving throw or be magically {@condition charmed} for 1 day. The {@condition charmed} target obeys the vampire's verbal commands. If the target suffers any harm or receives a suicidal command, it can repeat the saving throw, ending the effect on itself on a success. If the target's saving throw is successful or the effect ends for it, the target is immune to this vampire's Charm for the next 24 hours. The vampire can have only one target {@condition charmed} at a time. If it charms another, the effect on the previous target ends.

**Children of the Lower Planes (1/Day).** The pact vampire magically calls {@dice 2d4} dretches, {@dice 1d4} imps, or 1 bearded devil. The called Fiends arrive in {@dice 1d4} rounds, acting as allies of the vampire and obeying its spoken commands. The Fiends remain for 1 hour, until the vampire dies, or until the vampire dismisses them as a bonus action.

^Tags: #monster #type_undead