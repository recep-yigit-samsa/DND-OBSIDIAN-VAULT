# Ostinato

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ostinato | Aberration | 4 | 39 (6d8 + 12) | 15 | walk: 0 ft., fly: {'number': 50, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Cacophony Burst | 3d8 + 3 | - | - |
| Aural Symbiosis {@recharge} | 4d8 | 13 | - |
| Contagious Tune (1/Day) | 6d6 | 13 | - |


**Multiattack.** The ostinato makes two Cacophony Burst attacks.

**Cacophony Burst.** {@atk ms,rs} {@hit 7} to hit, range 60 ft., one target. {@h}16 ({@damage 3d8 + 3}) thunder damage.

**Aural Symbiosis {@recharge}.** One Humanoid that the ostinato can see within 5 feet of it must succeed on a {@dc 13} Charisma saving throw or the ostinato merges with the target, becoming an enjoyable, repetitive tune in its host's mind. The ostinato can't be targeted by any attack, spell, or other effect, and it can't attack. The host retains control of its body and is aware of the ostinato's presence only as a melody, not as a living entity. The host no longer needs to eat or drink, gains the ostinato's Magic Resistance trait, and has advantage on Charisma checks. In addition, the host has disadvantage on Wisdom saving throws, and it can't maintain {@status concentration} on spells or other effects. At the end of each long rest, the host can make a {@dc 13} Wisdom ({@skill Insight}) check, realizing that the music it hears comes from an external entity on a success. The Aural Symbiosis lasts until the host drops to 0 hp, the ostinato ends it as a bonus action, or the ostinato is forced out by an effect like the {@spell dispel evil and good} spell. When the Aural Symbiosis ends, the ostinato bursts out from the host's mind in a thunderous explosion of sound, reappearing in an unoccupied space within 5 feet of the host. Each creature within 15 feet of the ostinato when it exits, including the host, must make a {@dc 13} Constitution saving throw, taking 18 ({@damage 4d8}) thunder damage on a failed save, or half as much damage on a successful one. The host is immune to this ostinato's Aural Symbiosis for 24 hours after succeeding on the saving throw or after the Aural Symbiosis ends.

**Contagious Tune (1/Day).** While merged with a Humanoid host, the ostinato fills the minds of nearby creatures with the same catchy tune playing in its host's mind. Each creature within 30 feet of the ostinato's host must make a {@dc 13} Charisma saving throw, taking 21 ({@damage 6d6}) psychic damage on a failed save, or half as much damage on a successful one. The ostinato then gains temporary hp equal to the single highest amount of psychic damage dealt. A {@condition deafened} creature is immune to Contagious Tune.

^Tags: #monster #type_aberration