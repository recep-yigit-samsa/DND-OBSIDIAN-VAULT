# Firebird

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Firebird | Celestial | 4 | 88 (16d6 + 32) | 16 | walk: 20 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Beak | 1d6 + 4 + 2d6 | - | - |
| Talon | 2d4 + 4 + 2d6 | - | - |
| Blinding Ray {@recharge 5} | 5d6 | 15 | - |
| Healing Feathers (3/Day) | - | - | - |


**Multiattack.** The firebird makes one Beak attack and one Talon attack.

**Beak.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d6 + 4}) piercing damage plus 7 ({@damage 2d6}) fire damage.

**Talon.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}9 ({@damage 2d4 + 4}) slashing damage plus 7 ({@damage 2d6}) fire damage.

**Blinding Ray {@recharge 5}.** The firebird fires a burning ray of light from its tail feathers in a 30-foot line that is 5 feet wide. Each creature in that line must make a {@dc 15} Dexterity saving throw. On a failure, a creature takes 17 ({@damage 5d6}) fire damage and is {@condition blinded} until the end of its next turn. On a success, a creature takes half the damage and isn't {@condition blinded}.

**Healing Feathers (3/Day).** The firebird touches another creature, brushing its wings against the creature. The target magically regains 10 {@dice 3d6} hp and is freed from any disease, poison, blindness, or deafness.

^Tags: #monster #type_celestial