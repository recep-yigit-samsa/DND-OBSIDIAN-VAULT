# Phaerimm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Phaerimm | Aberration | 15 | 170 (20d10 + 60) | 18 | walk: 15 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d12 + 5 | - | - |
| Claw | 2d6 + 5 | - | - |
| Stinger | 2d6 + 5 | 18 | - |
| Implant | - | - | - |


**Multiattack.** The phaerimm makes four Claw attacks and then makes a Bite or Stinger attack. Alternatively, it uses Spellcasting and then makes two Claw attacks.

**Bite.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}18 ({@damage 2d12 + 5}) piercing damage.

**Claw.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d6 + 5}) slashing damage.

**Stinger.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d6 + 5}) piercing damage. If the target fails a {@dc 18} Constitution saving throw, they have the {@condition paralyzed} condition for 1 minute. The phaerimm's poison forces the {@condition paralyzed} target to float 5 feet above the ground. The target may repeat the saving throw at the end of each of it's turns.

**Implant.** The phaerimm makes a Stinger attack against a {@condition paralyzed} target. If the stinger hits, an egg is implanted in the target. This egg can only be removed by spells that cure disease, such as lesser restoration. If the egg is not removed within 90 days, the larva emerges, and the host is killed. A phaerimm has a single egg so may only use this ability once.

^Tags: #monster #type_aberration