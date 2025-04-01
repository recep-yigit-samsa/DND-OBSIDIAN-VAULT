# Eldritch Lich

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Eldritch Lich | Undead | 15 | 165 (22d8 + 66) | 17 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Parasitic Tentacle | 6d6 + 4 + 6d6 + 4 | 17 | - |
| Psychic Whisper | 6d6 + 4 | 17 | - |


**Multiattack.** The lich makes one Parasitic Tentacle attack or uses Spellcasting. The lich also uses Psychic Whisper twice.

**Parasitic Tentacle.** {@atk mw} {@hit 9} to hit, reach 10 ft., one creature. {@h}25 ({@damage 6d6 + 4}) piercing damage plus 25 ({@damage 6d6 + 4}) necrotic damage. The target must succeed on a {@dc 17} Constitution saving throw or be {@condition poisoned}. The {@condition poisoned} target can repeat the save at the end of each of its turns, ending the effect on itself on a success. The third time the target fails the save, the target dies and dissolves into a {@creature gibbering mouther} that obeys the lich and uses the target's initiative.

**Psychic Whisper.** The lich targets one creature it can see within 120 feet of itself. The target must succeed on a {@dc 17} Wisdom saving throw or take 25 ({@damage 6d6 + 4}) psychic damage and be {@condition stunned} until the end of the lich's next turn as incomprehensible whispers fill the target's mind.

^Tags: #monster #type_undead