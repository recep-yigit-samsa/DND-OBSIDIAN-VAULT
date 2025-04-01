# Nevermind Gnome Mastermind

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Nevermind Gnome Mastermind | Humanoid | 5 | 82 (15d6 + 30) | 15 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Clockwork Claw | 2d6 + 4 + 3d6 | 15 | - |
| Generate Gadget {@recharge 5} | - | - | - |
| Chattergrab | 7d8 | 16 | - |
| Phasmoball | 2d10 | 16 | - |
| Thunderscream | 6d6 | 16 | - |


**Multiattack.** The mastermind makes two Clockwork Claw attacks. The mastermind can replace one of these attacks with Generate Gadget if it's available.

**Clockwork Claw.** {@atk mw} {@hit 7} to hit, reach 20 ft., one target. {@h}11 ({@damage 2d6 + 4}) piercing damage, and if the target is a Medium or smaller creature, the target is {@condition grappled} (escape {@dc 15}). Until this grapple ends, the target takes 10 ({@damage 3d6}) piercing damage at the start of each of the mastermind's turns. The mastermind has two claws, each of which can grapple only one target.

**Generate Gadget {@recharge 5}.** The mastermind quickly assembles a clockwork gadget, producing one of the following effects (the mastermind's choice):

**Chattergrab.** Parts of this gadget look like gnashing metal teeth. This gadget hurtles toward a creature the mastermind can see within 60 feet of itself. The creature must succeed on a {@dc 16} Dexterity saving throw or take 31 ({@damage 7d8}) piercing damage and be {@condition incapacitated} until the start of the mastermind's next turn.

**Phasmoball.** The mastermind launches this gadget to a point the mastermind can see within 30 feet of itself, where the gadget unleashes a cloud of mind-warping gases in a 10-foot-radius sphere. Each creature within the sphere must succeed on a {@dc 16} Wisdom saving throw or take 11 ({@damage 2d10}) psychic damage and be {@condition frightened} of the mastermind until the start of the mastermind's next turn.

**Thunderscream.** This gadget emits a screeching wave of sound in a 30-foot cone originating from the mastermind. Each creature in that area must make a {@dc 16} Constitution saving throw, taking 21 ({@damage 6d6}) thunder damage on a failed save or half as much damage on a successful one.

^Tags: #monster #type_humanoid