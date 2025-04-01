# Scrapper

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Scrapper | Construct | 8 | 126 (12d10 + 60) | 18 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Spike Punch | 2d8 + 5 + 1d10 | - | - |
| Wires | 3d12 | 16 | - |
| Eye Beam {@recharge 5} | 8d10 | 16 | - |


**Multiattack.** The scrapper makes two Spike Punch attacks. It can replace one of those with a Wires attack.

**Spike Punch.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d8 + 5}) bludgeoning damage plus 5 ({@damage 1d10}) piercing damage.

**Wires.** {@atk mw} {@hit 8} to hit, reach 20 ft., one Large or smaller creature. {@h}The target has the {@condition grappled} condition (escape {@dc 16}) and must succeed on a {@dc 16} Strength saving throw or be pulled into an unoccupied space within 5 feet of the scrapper and take 19 ({@damage 3d12}) lightning damage. The scrapper can have only one creature {@condition grappled} in this way at a time.

**Eye Beam {@recharge 5}.** The scrapper shoots a magical beam from its extended eye at one creature it can see within 120 feet of itself. The target must make a {@dc 16} Dexterity saving throw, taking 44 ({@damage 8d10}) force damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct