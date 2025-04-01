# Al-Aeshma Genie

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Al-Aeshma Genie | Elemental | 9 | 149 (13d10 + 78) | 17 | walk: 30 ft., fly: {'number': 90, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Scimitar | 2d6 + 5 + 2d6 | - | - |
| Dust Devil | 2d6 + 2d6 | 17 | - |


**Multiattack.** The al-aeshma makes three Scimitar attacks. It can replace one attack with a use of Dust Devil or Spellcasting.

**Scimitar.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) slashing damage plus 7 ({@damage 2d6}) necrotic damage.

**Dust Devil.** The al-aeshma creates a swirling dust devil centered on a point it can see within 120 feet of it. The dust devil appears in the shape of a cylinder that is 30 feet tall with a 5-foot radius. Each creature in the area and each creature that enters the area for the first time on a turn or starts its turn there must succeed on a {@dc 17} Strength saving throw or be {@condition restrained}. While {@condition restrained}, a creature takes 7 ({@damage 2d6}) slashing damage and 7 ({@damage 2d6}) necrotic damage at the start of each of the al-aeshma's turns. A creature, including a {@condition restrained} creature, can take an action to free the {@condition restrained} creature by succeeding on a {@dc 17} Strength check. The al-aeshma can use a bonus action on its turn to move the dust devil up to 30 feet. A {@condition restrained} creature doesn't move with the dust devil when the dust devil moves and is freed if the dust devil moves out of its space. The dust devil lasts until the al-aeshma loses its {@status concentration} (as if {@status concentration||concentrating} on a spell), and the alaeshma can have only one dust devil active at a time.

^Tags: #monster #type_elemental