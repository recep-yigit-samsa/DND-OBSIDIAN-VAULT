# Dracolich

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dracolich | undead | {'cr': '17', 'xpLair': 20000} | 225 (18d12 + 108) | 20 | walk 40, burrow 30, fly 80 |

## Abilities

- **STR** 25 | **DEX** 10 | **CON** 23 | **INT** 19 | **WIS** 15 | **CHA** 21
- **Saving Throws:** DEX ++6, WIS ++8  
- **Skills:** Perception ++14, Stealth ++6  
- **Damage Resistances:** -  
- **Condition Immunities:** charmed, exhaustion, frightened, paralyzed, poisoned  
- **Senses:** blindsight 60 ft., darkvision 120 ft.  
- **Languages:** Common, Draconic

## Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dracolich fails a saving throw, it can choose to succeed instead.

**Life Suppression.** Creatures within 60 feet of the dracolich can't regain {@variantrule Hit Points|XPHB}.

**Magic Resistance.** The dracolich has {@variantrule Advantage|XPHB} on saving throws against spells and other magical effects.

**Soul Gem.** The dracolich has a magical gem. If the dracolich is destroyed while the gem is on the same plane of existence as it, the dracolich gains a new body in {@dice 1d20} days, regaining all its {@variantrule Hit Points|XPHB} and appearing within 5 feet of the gem.

The gem is a Tiny object that has AC 20; HP 50; and {@variantrule Immunity|XPHB} to Necrotic, Poison, and Psychic damage. The gem regains all its {@variantrule Hit Points|XPHB} at the end of every turn, but it turns to dust if reduced to 0 {@variantrule Hit Points|XPHB}. If the gem is destroyed, the dracolich can create a new one by completing an 8-hour ritual using a gem worth 1,000+ GP and by expending 5,000 GP, which the ritual consumes.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Rend | +13 to hit | 2d10 + 7 damage) Slashing damage plus 4 (1d8 damage) Necrotic | - |
| Necrotic Breath {@recharge 5} | DC 20 | 8d12 damage) Necrotic | Half Damage ✅ |

**Multiattack.** The dracolich makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast Ray of Sickness|XPHB spell (level 2 version).

**Rend.** {@atkr m} +13 to hit, reach 10 ft. {@h}18 (2d10 + 7 damage) Slashing damage plus 4 (1d8 damage) Necrotic damage.

**Necrotic Breath {@recharge 5}.** {@actSave con} DC 20 Saving Throw, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 52 (8d12 damage) Necrotic damage. {@actSaveSuccess} Half damage.

## Legendary Actions

**Pounce.** The dracolich moves up to half its {@variantrule Speed|XPHB}, and it makes one Rend attack.

**Sickening Ray.** The dracolich uses Spellcasting to cast Ray of Sickness|XPHB spell (level 2 version). The dracolich can't take this action again until the start of its next turn.

**Terrifying Presence.** {@actSave wis} DC 19 Saving Throw, each creature in a 30-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the dracolich. {@actSaveFail} 11 (2d10 damage) Psychic damage, and the target has the Frightened|XPHB condition condition until the end of its next turn. {@actSaveSuccessOrFail} The dracolich can't take this action again until the start of its next turn.



^Tags: #combat_ready #monster #type_undead #cr_{'cr': '17', 'xpLair': 20000} #legendary