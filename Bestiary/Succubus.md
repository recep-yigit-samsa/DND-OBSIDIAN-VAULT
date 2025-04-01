# Succubus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Succubus | Fiend | 4 | 71 (13d8 + 13) | 15 | walk: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Fiendish Touch | 2d10 + 5 | - | - |
| Charm | - | 15 | - |
| Draining Kiss | 3d8 | 15 | Half Damage ✅ |


**Multiattack.** The succubus makes one Fiendish Touch attack and uses Charm or Draining Kiss.

**Fiendish Touch.** {@atkr m} {@hit 7}, reach 5 ft. {@h}16 ({@damage 2d10 + 5}) Psychic damage.

**Charm.** The succubus casts {@spell Dominate Person|XPHB} (level 8 version), requiring no spell components and using Charisma as the spellcasting ability (spell save {@dc 15}).

**Draining Kiss.** {@actSave con} {@dc 15}, one creature {@condition Charmed|XPHB} by the succubus within 5 feet. {@actSaveFail} 13 ({@damage 3d8}) Psychic damage. {@actSaveSuccess} Half damage. {@actSaveSuccessOrFail} The target's {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by an amount equal to the damage taken.

^Tags: #monster #type_fiend