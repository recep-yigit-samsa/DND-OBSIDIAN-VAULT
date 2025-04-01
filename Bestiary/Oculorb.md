# Oculorb

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Oculorb | Aberration | 9 | 127 (15d10 + 45) | 13 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Dreadful Contact | 3d6 + 4 + 6d6 + 4 | - | - |
| Eye Beam | 3d6 + 4 | - | - |
| Antipathic Flood {@recharge 5} | - | - | - |
| Weeping Eyes | - | 16 | - |
| Withering Glare | 6d10 | 16 | - |


**Multiattack.** The oculorb makes two Dreadful Contact attacks or four Eye Beam attacks.

**Dreadful Contact.** {@atk mw} {@hit 5} to hit, reach 5 ft., one creature. {@h}14 ({@damage 3d6 + 4}) psychic damage, or 25 ({@damage 6d6 + 4}) psychic damage if the target has the {@condition frightened} condition.

**Eye Beam.** {@atk rs} {@hit 8} to hit, range 120 ft., one creature. {@h}14 ({@damage 3d6 + 4}) psychic damage.

**Antipathic Flood {@recharge 5}.** The oculorb releases a wave of negative emotions, choosing one of the following options:

**Weeping Eyes.** The oculorb weeps, releasing a wave of crushing despair. Each creature within 30 feet of the oculorb must make a {@dc 16} Constitution saving throw. On a failed save, a creature's speed is reduced to 0 feet until the end of the oculorb's next turn, and if the creature was {@status concentration||concentrating}, its {@status concentration} is broken.

**Withering Glare.** The oculorb's eyes unleash furious scarlet energy in a 60-foot cone. Each creature in that area must make a {@dc 16} Wisdom saving throw. On a failed save, a creature takes 33 ({@damage 6d10}) necrotic damage and has the {@condition frightened} condition for 1 minute. On a successful save, a creature takes half as much damage and isn't {@condition frightened}. A {@condition frightened} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a successful save.

^Tags: #monster #type_aberration