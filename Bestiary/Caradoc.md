# Caradoc

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Caradoc | Undead | 8 | 110 (20d8 + 20) | 14 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Withering Touch | 2d10 + 4 | - | - |
| Possession {@recharge 5} | - | 15 | - |


**Multiattack.** Caradoc makes two Withering Touch attacks.

**Withering Touch.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d10 + 4}) necrotic damage.

**Possession {@recharge 5}.** One Humanoid that Caradoc can see within 5 feet of himself must succeed on a {@dc 15} Charisma saving throw or be possessed by him; he then disappears, and the target is {@condition incapacitated} and loses control of its body. Caradoc now controls the body but doesn't deprive the target of awareness. Caradoc can't be targeted by any attack, spell, or other effect, except ones that turn Undead, and he retains his alignment, Intelligence, Wisdom, and Charisma, immunity to being {@condition charmed} and {@condition frightened}, and his Divisive Whispers bonus action. He otherwise uses the possessed target's statistics but doesn't gain access to the target's knowledge, class features, or proficiencies. The possession lasts until the body drops to 0 hit points, Caradoc ends it as a bonus action, or he is turned or forced out by an effect like the {@spell dispel evil and good} spell. When the possession ends, Caradoc reappears in an unoccupied space within 5 feet of the body. The target is immune to Caradoc's Possession for 24 hours after succeeding on the saving throw or after the possession ends.

^Tags: #monster #type_undead