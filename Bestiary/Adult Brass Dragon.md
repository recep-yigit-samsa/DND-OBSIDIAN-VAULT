# Adult Brass Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Brass Dragon | Unknown | {'cr': '13', 'xpLair': 11500} | 172 (15d12 + 75) | 18 | walk: 40 ft., burrow: 30 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d10 + 6 + 1d8 | - | - |
| Fire Breath {@recharge 5} | 10d8 | 18 | Half Damage ✅ |
| Sleep Breath | - | 18 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Sleep Breath or (B) Spellcasting to cast {@spell Scorching Ray|XPHB}.

**Rend.** {@atkr m} {@hit 11}, reach 10 ft. {@h}17 ({@damage 2d10 + 6}) Slashing damage plus 4 ({@damage 1d8}) Fire damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 18}, each creature in a 60-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 45 ({@damage 10d8}) Fire damage. {@actSaveSuccess} Half damage.

**Sleep Breath.** {@actSave con} {@dc 18}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target has the {@condition Incapacitated|XPHB} condition until the end of its next turn, at which point it repeats the save. {@actSaveFail 2} The target has the {@condition Unconscious|XPHB} condition for 10 minutes. This effect ends for the target if it takes damage or a creature within 5 feet of it takes an action to wake it.

^Tags: #monster #type_unknown