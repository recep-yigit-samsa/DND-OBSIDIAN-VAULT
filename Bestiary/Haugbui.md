# Haugbui

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Haugbui | Undead | 13 | 153 (18d8 + 72) | 15 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Psychic Blast | 5d8 + 5 | - | - |
| Invisibility | - | - | - |


**Multiattack.** The haugbui makes three Psychic Blast attacks. It can replace one attack with a use of Spellcasting.

**Psychic Blast.** {@atk ms,rs} {@hit 10} to hit, range 120 ft., one target. {@h}27 ({@damage 5d8 + 5}) psychic damage.

**Invisibility.** The haugbui magically turns {@condition invisible} until it attacks or casts a spell, or until its {@status concentration} ends (as if {@status concentration||concentrating} on a spell). Any equipment the haugbui wears or carries is {@condition invisible} with it.

^Tags: #monster #type_undead