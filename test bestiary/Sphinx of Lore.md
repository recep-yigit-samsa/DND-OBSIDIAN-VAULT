# Sphinx of Lore

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sphinx of Lore | celestial | {'cr': '11', 'xpLair': 8400} | 170 (20d10 + 60) | 17 | walk 40, fly 60 |

## Abilities

- **STR** 18 | **DEX** 15 | **CON** 16 | **INT** 18 | **WIS** 18 | **CHA** 18
- **Saving Throws:** -  
- **Skills:** Arcana ++12, History ++12, Perception ++8, Religion ++12  
- **Damage Resistances:** necrotic, radiant  
- **Condition Immunities:** charmed, frightened  
- **Senses:** truesight 120 ft.  
- **Languages:** Celestial, Common

## Traits

**Inscrutable.** No magic can observe the sphinx remotely or detect its thoughts without its permission. Wisdom ({@skill Insight|XPHB}) checks made to ascertain its intentions or sincerity are made with {@variantrule Disadvantage|XPHB}.

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the sphinx fails a saving throw, it can choose to succeed instead.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Claw | +8 to hit | 3d6 + 4 damage) Slashing | - |
| Mind-Rending Roar {@recharge 5} | DC 16 | 10d6 damage) Psychic | - |

**Multiattack.** The sphinx makes three Claw attacks.

**Claw.** {@atkr m} +8 to hit, reach 5 ft. {@h}14 (3d6 + 4 damage) Slashing damage.

**Mind-Rending Roar {@recharge 5}.** {@actSave wis} DC 16 Saving Throw, each enemy in a 300-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the sphinx. {@actSaveFail} 35 (10d6 damage) Psychic damage, and the target has the Incapacitated|XPHB condition condition until the start of the sphinx's next turn.

## Legendary Actions

**Arcane Prowl.** The sphinx can teleport up to 30 feet to an unoccupied space it can see, and it makes one Claw attack.

**Weight of Years.** {@actSave con} DC 16 Saving Throw, one creature the sphinx can see within 120 feet. {@actSaveFail} The target gains 1 Exhaustion|XPHB condition level. While the target has any Exhaustion|XPHB condition levels, it appears {@dice 3d10} years older. {@actSaveSuccessOrFail} The sphinx can't take this action again until the start of its next turn.



^Tags: #combat_ready #monster #type_celestial #cr_{'cr': '11', 'xpLair': 8400} #legendary